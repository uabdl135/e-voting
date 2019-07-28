This project is aimed at developing an e-voting system using blockchain. The idea is to use multiple blockchains, one for each district and verify them at a later date(verification day). An application will be launched for each district on the election day. Each individual's vote will comprise a block for that district's blockchain. Each block will contain the following data: 1.) transaction ID - a string which will contain the hash of the Voter ID number to ensure that multiple votes are not cast by the same user 2.) a date-time stamp. 3.) data - the political party the user has voted for. 4.)District ID - To store which blockchain should the current block be a part of. 5.)polling booth number.
Each user will have to go to the nearest polling booth to register themselves which will extend till the date of the election. At the time of user registration, the user will be given a fixed randomly generated password of sufficient length to prevent brute force attacks. The application will take voter ID as username and the password to login and once a user votes, a set of admin systems(100 or more) will verify the addition of that block to the blockchain. The username is not stored to maintain anonymity of voters. Once this is done, the electon commission will verify the final votes and begin the final count at a later date. The votes will also be counted in real time to ensure that the number of votes never decrease. The distributed ledger will only be available to the admin systems and they too will only have the authority to add and verify a block. No editing of blocks will be allowed to any user or admin. Once the app is launched for a particular district, a genesis block is created which will signify the official commencement of elections in that district.
Once the election ends a block will be added to the end of that chain (marking the end of election for that district) which will be referred by the genesis block of the next district thereby adding each district's blockchain to the master blockchain. In effect ths will create multiple sub-blockchains constituting the master blockchain (having a master genesis block) which will be shared among the admin systems as discussed earlier. The number of admin systems(to be decided by the electiono commission) will be decided taking feasability and budget into account.

# blockchain-developer-bootcamp-final-project


## Project: Answer Checker

The aim of this project is to make a simple blockchain answer checker, for an admin to submit solution questions and users to answer.

### Project Scope

To allow the owner of the contract to submit 3 answers for a user to attempt to get the same answers.

+ An ERC1155 token will be minted on success of the answers.

### User story

+ Owner will submit 3 answers
+ Owner can check the answers without affecting the amount of attempts
+ User will submit their 3 answers
+ The number of attmepts will be recored (total and for individual user (address))
+ If correct user can mint an NFT
+ NFT will be different depening on how many total correct answers have been given
+ Only one NFT can be minted per user


## Deployed Contract Address
Network: Rinkeby
Address: 0xc00A82A6E05107c0C9349A0Bd8167D62C508fd7C

## Deployed DApp
https://unruffled-swartz-eb915f.netlify.app/

## Guided Walkthrough
https://www.loom.com/share/f1ef4c5d9d3d4d0ca58fe1a08d45e545?sharedAppSource=personal_library



## Testing Process
I used the unit testing capabilities in remix - https://remix.ethereum.org/

Testing in Remix process
1. Go to https://remix.ethereum.org/
2. Paste the contents of my two smart contracts into new files, keeping the naming convention
3. compile the AnswerChecker.sol
4. Add the unit testing plugin - https://remix-ide.readthedocs.io/en/latest/unittesting.html
5. Select the AnserCheker_test.sol contract
6. Click run
7. await results

## Personal Ethereum address
(for certification if applicable)
0x0D389aa79159030f4c7651eA98F56193f448C3F9
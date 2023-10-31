# A Decentralized Auction House for Fine Art 

## Instructions for Local Deployment
1. Download the prerequisites to run the application. Detailed instructions for this step can be found in Sections 1 and 2 in `documents/setup_instructions.pdf`
2. Run Ganache, and connect MetaMask to Ganache. Detailed instructions for this step can be found in Sections 3.1 and 3.2 in `documents/setup_instructions.pdf`
3. Clone the repo
```
```
4. Migrate to root folder of the repo
5. If you would like to reinitialize the app (if for example, you used this application in the past), you will need to delete any `.json` files in `build/contracts`
6. Test the contract functions using unit tests specified in `test/TestAuction.sol` (not essential)
```
$ truffle test
```
7. Compile the contracts `Auction.sol` and `Migrations.sol` located in `contracts/`
```
$ truffle compile
```
8. Migrate the contract to your local server through Ganache. The contract needs to be compiled (Step 7) before it can be migrated
```
$ truffle migrate
```
9. Run the local server
```
$ npm run dev
```

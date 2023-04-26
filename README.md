# Aimed at NFT for Students,

Similar to OpenSeas, you can create and purchase your own NFT's.

### Home Page

<img src="https://github.com/ryan10projects/Nft_4_Students/blob/main/Home%20page.PNG" width="600" title="Home Page">

### Purchase through metamask

<img src="https://github.com/ryan10projects/Nft_4_Students/blob/main/Metamask%20wallet%20purchases.PNG" width="600">

### Upload NFT using metaMask

<img src="https://github.com/ryan10projects/Nft_4_Students/blob/main/transactions.PNG" width="600">

### Transaction completed

<img src="https://github.com/ryan10projects/Nft_4_Students/blob/main/Purchase%20complete.PNG" width="600">

### Listed NFts by User

<img src="https://github.com/ryan10projects/Nft_4_Students/blob/main/listed.PNG" width="600" >

### Setup

# 1. Clone/Download the Repository
# 2. Install Dependencies:
$ cd nft_marketplace
$ npm install
# 3. Boot up local development blockchain
$ cd nft_marketplace
$ npx hardhat node
# 4. Connect development blockchain accounts to Metamask
Copy private key of the addresses and import to Metamask
Connect your metamask to hardhat blockchain, network 127.0.0.1:8545.
If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.
# 5. Create an infura account, and paste the required details in Create.js file inside frontend directory 
# 6. Migrate Smart Contracts
npx hardhat run src/backend/scripts/deploy.js --network localhost
# 7. Run Tests
$ npx hardhat test
# 8. Launch Frontend
$ npm run start

# MeterQuest Marketplace

View Demo Video here in the end: [https://youtu.be/RY-Pnzh9I0E](https://youtu.be/RY-Pnzh9I0E)
This is the place to shop your game assets using the DGN game token and later use these to equip the purchased heroes inside the dungeon based MeterQuest Game. Gas fees are paid in MTR tokens

Mint items, buy and sell and also view them in the collectibles dashboard.

# Smart Contracts Deployed to Meter Warring Stakes testnet

<img width="1440" alt="image" src="https://user-images.githubusercontent.com/43913734/169712415-c8e2ea29-224f-4998-be02-645c5d4f104a.png">


`DGNTokenaddress = "0x121f0a4dE3b8503a884db1DF1768bc894BEa82B2"`

[Verify Here on Meter Warring Stakes testnet explorer](https://scan-warringstakes.meter.io/address/0x121f0a4dE3b8503a884db1DF1768bc894BEa82B2)

`nftaddress = "0x04F6d3232ae9CE3367e5F83ed0586A48d813bA99"` 

[Verify Here on Meter Warring Stakes testnet explorer](https://scan-warringstakes.meter.io/address/0x04F6d3232ae9CE3367e5F83ed0586A48d813bA99)

`nftmarketaddress ="0xD2f797A61611394D4CAb688Fa4a39BaDB9640727"`

[Verify Here on Meter Warring Stakes testnet explorer](https://scan-warringstakes.meter.io/address/0xD2f797A61611394D4CAb688Fa4a39BaDB9640727?tab=0&p=1)

<img width="1440" alt="image" src="https://user-images.githubusercontent.com/43913734/169712256-a5e0822e-e66a-4431-bdca-b895f91d9c15.png">
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/43913734/169712313-f62851c6-7395-4ace-9991-1fe3c7a56bd6.png">
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/43913734/169712353-b7ed822d-14ff-4d29-a2ab-67e8a32b962a.png">


Refer to `hardhat.config.js`:

`module.exports = {
  defaultNetwork: "",
  networks: {
    networks: {
    localhost: {
        url: "http://127.0.0.1:7545"
    },
    meter_testnet: {
      url: "https://rpctest.meter.io",
      accounts:
        process.env.PRIVATE_KEY !== undefined ? [process.env.PRIVATE_KEY] : [],
    },
  },
  solidity: "0.8.4",
  mocha: {
    timeout: 600000
  }
};`


# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

# MeterQuest Marketplace

This is the place to shop your game assets using the DGN game token and later use these to equip the purchased heroes inside the dungeon based MeterQuest Game. Gas fees are paid in MTR tokens



# Smart Contracts Deployed to Meter Warring Stakes testnet

`DGNTokenaddress = "0x121f0a4dE3b8503a884db1DF1768bc894BEa82B2"`

[Verify Here on Meter Warring Stakes testnet explorer](https://scan-warringstakes.meter.io/address/0x121f0a4dE3b8503a884db1DF1768bc894BEa82B2)

`nftaddress = "0x04F6d3232ae9CE3367e5F83ed0586A48d813bA99"` 

[Verify Here on Meter Warring Stakes testnet explorer](https://scan-warringstakes.meter.io/address/0x04F6d3232ae9CE3367e5F83ed0586A48d813bA99)

`nftmarketaddress ="0xD2f797A61611394D4CAb688Fa4a39BaDB9640727"`

[Verify Here on Meter Warring Stakes testnet explorer](https://scan-warringstakes.meter.io/address/0xD2f797A61611394D4CAb688Fa4a39BaDB9640727?tab=0&p=1)



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

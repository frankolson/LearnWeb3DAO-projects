# DAO App Contracts

- Fake NFT Marketplace contract address on the Rinkeby test network: `0xA6Ea35b9DFff7D3Ff8d40cc063B4B747AbacD420`.
- DAO contract address on the Rinkeby test network: `0x994732Fba0277F0c67E49EF43b3244e04C2dE38E`.

## Deploying

Make sure you have a `.env` file in the root of this project with the following content:

```
// Go to https://www.alchemyapi.io, sign up, create
// a new App in its dashboard and select the network as Rinkeby, and replace "add-the-alchemy-key-url-here" with its key url
ALCHEMY_API_KEY_URL="add-the-alchemy-key-url-here"

// Replace this private key with your RINKEBY account private key
// To export your private key from Metamask, open Metamask and
// go to Account Details > Export Private Key
// Be aware of NEVER putting real Ether into testing accounts
RINKEBY_PRIVATE_KEY="add-the-rinkeby-private-key-here"
```
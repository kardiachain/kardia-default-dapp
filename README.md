# Kardia Default DApp list

This is a repository containing default DApp for KardiaChain Wallet.

To add your DApp to our list, create a Pull Request to this repository. The PR should contain:
1. DApp's logo: a 64x64 PNG image with border radius 16px in `logo` folder
2. DApp's infomation: add your DApp's infomation to `dapp.json` file. For example:
```json
{
  "name": "KAIDex",
  "url": "https://kaidex.io",
  "icon": "https://raw.githubusercontent.com/kardiachain/kardia-default-dapp/master/logo/kaidex.png",
  "categories": [
    "DEX"
  ]
}
```
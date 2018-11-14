# dApps
Here you can submit your Ethereum or Ethereum Classic dApps to Saturn Network's collection. Currently submitting your dApp allows it to be pre-listed in Saturn Wallet, however, submitting your dApp means the information may be used across all our products.
## How to submit your dApp correctly
* Step 1: Prepare a logo for your dApp, it needs to be 200x200 in PNG format on a transparent background.
* Step 2: Fork the project's repository.
* Step 3: Upload your dApp's logo to the relevant directory: Ethereum dApps go in dapps/eth/logo/ whereas Ethereum Classic dApps go in dapps/etc/logo/.
* Step 4: Add your dApps's additional information to the relevant JSON file: Ethereum dApps use dapps/eth/dapps.json whereas Ethereum Classic dapps use dapps/etc/dapps.json. Follow this format:
```
 {
    "name": "dApp Name",
    "address": "Contract address",
    "website": "Your website",
    "forum": "Link to your announcement topic on https://forum.saturn.network/",
    "logo": "https://saturn-network.github.io/dapps/eth or etc/logo/yourdapp.png"
  }
  ```
## **Please note we have to manually approve pull requests and we may refuse requests containing abusive content or misleading information that will alienate our website visitors or wallet users.**

# Generate v1 Address

## 🧩 Prerequisites

Please **clone the source code from the official repository** at:  
👉 [https://github.com/zorp-corp/nockchain](https://github.com/zorp-corp/nockchain)

Then compile the **latest version** of `nockchain-wallet` yourself.

If you happen to encounter difficulties during the compilation process and would prefer a quicker setup, you may also **download our precompiled latest release of `nockchain-wallet`** to proceed with the steps below.

---

## ⚙️ Generate a v1 Address

Once the wallet is ready, run the following command in your terminal to generate a mining address (v1 address):

First:
```bash
chmod +x nockchain-wallet
```

```bash
./nockchain-wallet generate-mining-pkh
```

After execution, you'll receive a new **v1 public key address** that can be used for mining or receiving payments.
If the command is not recognized, please make sure you are using the **latest version** of nockchain-wallet.

---

## 💡 Manage Your Addresses

To view all your current addresses, run:

```bash
./nockchain-wallet list-master-addresses
```

To set which address should be used for transfers or other operations, run:

```bash
./nockchain-wallet set-active-master-addres <address>
```

Please note that you can only use a v1 address to initiate transactions after block height 39000.

For more commands and detailed usage instructions, please refer to the official documentation:  
👉 [https://github.com/zorp-corp/nockchain/blob/master/crates/nockchain-wallet/README.md](https://github.com/zorp-corp/nockchain/blob/master/crates/nockchain-wallet/README.md)


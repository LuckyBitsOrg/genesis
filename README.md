# LuckyBits Genesis Configuration

Welcome to the **LuckyBits Genesis Configuration** repository! Here, you'll find everything you need to set up your LuckyBits node and start interacting with the network.

### Chain Details:
- **Chain ID:** 777 (lucky number)
- **Ticker:** BIT
- **Website:** [https://luckybits.org/](https://luckybits.org/)

## How to Set Up Your Node

To start using LuckyBits, you'll need to import the genesis configuration and initialize your node. Follow the steps below.

### Step 1: Import Genesis

To initialize your node with the LuckyBits genesis configuration, run the following command:

```./geth --datadir folder_name init luckybits.json```

Replace `folder_name` with the name of the directory where your node's data will be stored.

### Step 2: Run Your Node

After importing the genesis, you can start your node using the following command:

```./geth --datadir folder_name --networkid 777 --syncmode "full"```

Make sure to replace `folder_name` with your node's data directory.
Additional Information

- LuckyBits is an EVM-compatible blockchain network, allowing you to deploy dApps, NFTs, and smart contracts.
- For further details and updates, visit our website: https://luckybits.org/

Happy mining! 💎🍀


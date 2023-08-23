# NextJS NFT Marketplace with TheGraph

This is a frontend file for decentralized nft marketplace in nextjs.

## Functionalities
The frontend provide these functionalities
- You can list new NFT's.
- You can update the listed NFT's.
- You can buy NFT's listed by others.
- Cancel or Delete your NFT from the marketplace.
- Withdraw payments of the sold NFT's.
## 1. Git clone the contracts repo

In it's own terminal / command line, run: 

```
git clone https://github.com/highHumann/frontend-nft-marketplace
cd frontend-nft-marketplace
yarn
```

## 2. Deploy to sepolia 

After installing dependencies, deploy your contracts to sepolia:

```
yarn hardhat deploy --network sepolia
```

## 3. Deploy your subgraph

Then, make a `.env` file and place your temporary query URL into it as `NEXT_PUBLIC_SUBGRAPH_URL` as shown in `.env.example`


## 4. Start your UI

Make sure that:
- In your `networkMapping.json` you have an entry for `NftMarketplace` on the sepolia network. 
- You have a `NEXT_PUBLIC_SUBGRAPH_URL` in your `.env` file.
  
## Contributing

=Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
```
yarn dev
```


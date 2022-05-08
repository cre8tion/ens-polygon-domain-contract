# ENS Polygon Domain Contract

This project demonstrates a Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

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

## Testing

```shell
npx hardhat run scripts/run.js

```

## Deployment

```shell
npx hardhat run scripts/deploy.js --network mumbai
```

## A note on contract redeploys

Let's say you want to change your contract. You'd need to do 3 things:

1. We need to deploy it again.
2. We need to update the contract address on our frontend.
3. We need to update the abi file on our frontend.

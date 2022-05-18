## A cryptocurrency with Node and crypto-js

#### Properties of a block

The blockchain is composed of several blocks. Every block in the chain is made up of the following properties:

- Proof of work: The amount of computational effort required to get a block hash
- Block hash: Block ID derived through cryptographic calculation
- Timestamp: Time when the block was created
- Index: Block’s position on the chain
- Data recorded on the blockchain
- The previous block’s hash

#### imported the Secure Hash Algorithm (SHA256) from the crypto-js package, which helps us to encrypt our block hash ID.

#### To install the dependency, run the following command in your terminal:

```bash
//install the crypto-js dependency
npm install crypto-js
```

We’ll use a single file for this project, run the code with the following command in the terminal:

```sh
node nodejscoin
```

For a detailed explanation on how things work, check out the [guide](https://blog.logrocket.com/build-cryptocurrency-node-js-blockchain/) and [docs for crypto-js](https://www.npmjs.com/package/crypto-js).


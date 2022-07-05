# 🛌 🌿 Lazy minting contract

```bash
npm install

npm run test --network hardhat
```

```text
> npx hardhat test --network hardhat

Compiling 15 files with 0.8.4
Compilation finished successfully


  LazyNFT
    √ Should deploy (1293ms)
    √ Should mint an NFT from a signed transaction (230ms)
    √ Should fail to mint an NFT that's already been claimed (221ms)
    √ Should fail to mint an NFT voucher that's signer and signerVerify are different (189ms)
    √ Should fail to mint an NFT voucher that's been modified (128ms)
    √ Should fail to mint an NFT voucher with an invalid signature (116ms)


  6 passing (2s)
```

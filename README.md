# CMv2-starter

## Installation
```
yarn install
yarn start
```

## Setup

1. Prepare the assets
1. Run the CM V2 `upload` command to generate the Candy Machine ID:
1. Rename .env-template to .env and populate the variables

```
ts-node ~/metaplex-foundation/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts upload \
--env devnet \
--keypair ~/.config/solana/devnet.json \
--config-path config.json \
./assets
```

-------------------



This was built on [metaplex](https://github.com/metaplex-foundation/metaplex) version v1.1.0

# foundry-starter-kit

## Usage

### Build

```shell
forge build
```

### Test

```shell
forge test
```

### Deploy

```shell
forge script script/Deploy.s.sol:Deploy \
--chain-id $CHAIN_ID \
--rpc-url $RPC_URL \
--private-key $PRIVATE_KEY \
--etherscan-api-key $ETHERSCAN_API_KEY \
--verifier-url $VERIFIER_URL \
--broadcast --legacy --ffi --verify -vvvv #--resume

forge script script/Deploy.s.sol:Deploy --sig 'sync()' --rpc-url $RPC_URL --private-key $PRIVATE_KEY --broadcast --legacy --ffi
```

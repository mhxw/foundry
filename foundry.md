# Foundry

### forge test

.env

```env
ARBITRUM_ONE_RPC_URL=""
ARBITRUM_SEPOLIA_RPC_URL=""
ETHERSCAN_API_KEY=""
```

主网模拟测试

```
source .env
forge test --match-contract UniversalRouter \
-vvv --fork-url=$ARBITRUM_ONE_RPC_URL \
--fork-block-number 196765174
```
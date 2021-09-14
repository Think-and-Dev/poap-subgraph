# POAP Subgraph

This Subgraph sources events from the POAP contract in different networks.

## Deploying the subgraph:
We are using the [Legacy Explorer](https://thegraph.com/docs/legacyexplorer/deploy-subgraph-hosted)

**First time only**
```ssh
yarn install
npx graph auth --product hosted-service <ACCESS_TOKEN>
npx graph init --product hosted-service <GITHUB_USER>/<SUBGRAPH NAME>
```

Available networks: ethereum, xdai, sokol, kovan, ropsten, celo-alfajores, celo

```ssh
yarn prepare:<network>
yarn codegen
yarn build
yarn deploy:<network>
```

## Deployments

### Ethereum
Endpoint: [https://api.thegraph.com/subgraphs/name/poap-xyz/poap](https://api.thegraph.com/subgraphs/name/poap-xyz/poap) \
Subgraph page: [https://thegraph.com/explorer/subgraph/poap-xyz/poap](https://thegraph.com/explorer/subgraph/poap-xyz/poap)

### XDai
Endpoint: [https://api.thegraph.com/subgraphs/name/poap-xyz/poap-xdai](https://api.thegraph.com/subgraphs/name/poap-xyz/poap) \
Subgraph page: [https://thegraph.com/explorer/subgraph/poap-xyz/poap-xdai](https://thegraph.com/explorer/subgraph/poap-xyz/poap)


### Sokol
Endpoint: [https://api.thegraph.com/subgraphs/name/poap-xyz/poap-sokol](https://api.thegraph.com/subgraphs/name/poap-xyz/poap) \
Subgraph page: [https://thegraph.com/explorer/subgraph/poap-xyz/poap-sokol](https://thegraph.com/explorer/subgraph/poap-xyz/poap)

### Ropsten
Endpoint: [https://api.thegraph.com/subgraphs/name/poap-xyz/poap-ropsten](https://api.thegraph.com/subgraphs/name/poap-xyz/poap) \
Subgraph page: [https://thegraph.com/explorer/subgraph/poap-xyz/poap-ropsten](https://thegraph.com/explorer/subgraph/poap-xyz/poap)

### Kovan
Endpoint: [https://api.thegraph.com/subgraphs/name/poap-xyz/poap-kovan](https://api.thegraph.com/subgraphs/name/poap-xyz/poap) \
Subgraph page: [https://thegraph.com/explorer/subgraph/poap-xyz/poap-kovan](https://thegraph.com/explorer/subgraph/poap-xyz/poap)


Deployed to https://thegraph.com/explorer/subgraph/pmprete/Poapalfajores

Subgraph endpoints:
Queries (HTTP):     https://api.thegraph.com/subgraphs/name/pmprete/poapalfajores
Subscriptions (WS): wss://api.thegraph.com/subgraphs/name/pmprete/poapalfajores
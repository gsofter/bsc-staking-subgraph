# Subgraph for BSC Staking

### Prerequisites

Install The Graph CLI

```
# NPM
$ npm install -g @graphprotocol/graph-cli

# Yarn
$ yarn global add @graphprotocol/graph-cli
```

### Scripts to runs

```
$ graph codegen
$ graph build

$ graph auth --product hosted-service <ACCESS_TOKEN>
$ graph deploy --product hosted-service <GITHUB_USER>/<SUBGRAPH NAME>
```

To learn how to delopy the subgraph in more detail, take a look of [guide doc](https://thegraph.com/docs/developer/quick-start#1-install-the-graph-cli).

Check deployed subgraph [here](https://thegraph.com/hosted-service/subgraph/gsofter/bsc-staking).

## Eth Denver Bounty - 2020

### Who are we?
Ethereum Classic Labs is a blockchain accelerator, investor, and core infrastructure developer. We provide tools and funding to help developers build on the Ethereum Classic blockchain.

### Bounty

#### Build a inspired dApp or tool using at least one of our ETCLabs Core / OpenRPC Tools
We want you to build a cool tool or dApp that uses at least one of our developer tools. The more tools you use in your project the better! A maximum of 2 winners will be rewarded $500 in ETH each.

#### The tools
* [Multi-Geth Client](https://multi-geth.org/) - An ETH and ETC compatible client
* [Jade Service Runner](https://github.com/etclabscore/jade-service-runner) - Envoy proxy for decentralized services
* [Jade Desktop](https://github.com/etclabscore/jade-desktop) - a ux for running chains
* [Ethereum JSON RPC Spec Client](https://github.com/etclabscore/ethereum-json-rpc-specification#clients)
* [Expedition](http://expedition.dev/) - a self contained block explorer
* [Signatory](http://signatory.dev/) a code signing service
* [Open-RPC Client Generator](https://github.com/open-rpc/generator-client) - Generate OpenRPC/JSON-RPC clients
* [Open-RPC Server Generator](https://github.com/open-rpc/server-js) - Generate OpenRPC/JSON-RPC server interface
* [Open-RPC Typings Generator](https://github.com/open-rpc/typings) - Generate Open-RPC Types
* [Open-RPC React Docs Generator](https://github.com/open-rpc/docs-react)
* [React Typescript Project Generator](https://github.com/etclabscore/pristine-typescript-react)
* [Typescript Material UI Gatsby Generator](https://github.com/etclabscore/pristine-typescript-gatsby-react-material-ui)

#### The guides
[Jade Service Runner and Desktop](https://jade.builders/getting-started/)
[Multi Geth Getting Overview](https://multi-geth.org/overview)
[OpenRPC Getting Started](https://open-rpc.org/getting-started)
[Signatory Getting Started](https://signatory.dev/getting-started)

#### Example Inspiration

* A wallet that uses Signatory
* Contract state explorer that uses Ethereum JSON RPC Spec
* A L2 state tracker with an Open-RPC server

#### Judging Criteria
We will determine the winner of the bounty using the following criteria.
* Originality
* Utility to blockchain technology
* Number of Tools used
* Technicality
* If project is smart contract based then it should be deployed to Kotti Chain here's the faucet(https://kottifaucet.me)

#### Amount: 
$500 in ETH per valid submission. Up to 2 winners!

#### Connect to ETC full nodes from public RPC Endpoints
- ##### ETC Mainnet
  - https://services.jade.builders/multi-geth/mainnet/1.9.9
  - https://www.ethercluster.com/etc
- ##### ETC Kotti Testnet
  - https://services.jade.builders/multi-geth/kotti/1.9.9
  - https://www.ethercluster.com/kotti
- ##### ETC Mordor Testnet
  - https://services.jade.builders/multi-geth/mordor/1.9.9

##### Try it out!
[Multi Geth](https://multi-geth.org/api-documentation/)
or 
```sh
curl  -X POST -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","method":"eth_chainId","params": [],"id":1}' https://services.jade.builders/multi-geth/kotti/1.9.9
```
result
```
{"jsonrpc":"2.0","id":1,"result":"0x6"}
```
##### Need help find us on Discord!
https://discord.gg/8b7HJe5



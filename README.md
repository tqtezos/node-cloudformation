# node-cloudformation
CloudFormation scripts for use along with [node-docker repo](https://github.com/tqtezos/node-docker) and [tezos-updater repo](https://github.com/tqtezos/tezos-updater) to be used for deploying public nodes on AWS.

1. Fork all repositories. 
2. Update CloudFormation scripts for tezos-updater and frontnode-standalone to point to your github account (instead of tqtezos) and change testnet to the appropriate branch you want to deploy if you'd like to deploy a mainnet or zeronet node. 
3. Follow steps on aws console CloudFormation to deploy in order: VPCs, tezos-updater, frontnode-standalone. 


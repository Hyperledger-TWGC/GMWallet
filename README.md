# GMWallet
Sample implementation for GM curve based wallet.
The goal for this project is providing a sample implementation for GM curve based wallet fro fabric gateway SDK usage.

> Notice: this is not a wallet product

## Motivation
in coming fabric gateway sdk, we'd better have a GM wallet implementation. so that we can have a sample implementation for [hyperledger/fabric-rfcs#34](https://github.com/hyperledger/fabric-rfcs/pull/34#discussion_r739065194)

## Design
Ref to [Mark S. Lewis](https://github.com/bestbeforetoday) comments at [hyperledger/fabric-rfcs#34](https://github.com/hyperledger/fabric-rfcs/pull/34#discussion_r739065194)

- Uses [application-provided hashing implementation](https://hyperledger.github.io/fabric-gateway/main/api/java/org/hyperledger/fabric/client/Gateway.Builder.html#hash(java.util.function.Function)) so any hashing algorithm can easily be used with no SDK changes.
- Uses [application-provided signing implementation](https://hyperledger.github.io/fabric-gateway/main/api/java/org/hyperledger/fabric/client/Gateway.Builder.html#signer(org.hyperledger.fabric.client.identity.Signer)) so any encryption algorithm or implementation can easily be used with no SDK changes.

## Languages: 
go, java, nodejs, typescript

## Contributors
<a href="https://github.com/Hyperledger-TWGC/GMWallet/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Hyperledger-TWGC/GMWallet" />
</a>

## Contribute
Here is steps in short for any contribution. 
1. check license and code of conduct
1. fork this project
1. make your own feature branch
1. change and commit your changes, please use `git commit -s` to commit as we enabled [DCO](https://probot.github.io/apps/dco/)
1. raise PR

## Code of Conduct guidelines
Please review the Hyperledger [Code of
Conduct](https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct)
before participating. It is important that we keep things civil.

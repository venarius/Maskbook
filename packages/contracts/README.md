# Contracts

## Compile contracts typing

```console
$ npm start

> start
> ts-node compile-contracts.ts

$ npx prettier --write * # cwd: packages/contracts/types
Airdrop.d.ts 178ms
BalanceChecker.d.ts 12ms
BulkCheckout.d.ts 32ms
COTM_Token.d.ts 36ms
ElectionToken.d.ts 35ms
ERC20.d.ts 17ms
ERC721.d.ts 22ms
ExchangeProxy.d.ts 20ms
HappyRedPacket.d.ts 18ms
ITO.d.ts 27ms
MaskITO.d.ts 33ms
Multicall.d.ts 6ms
Pair.d.ts 30ms
RouterV2.d.ts 24ms
Splitter.d.ts 5ms
types.d.ts 14ms
$ git add . # cwd: packages/contracts/abis
$ git add . # cwd: packages/contracts/types
```

# Bot-Snipping-Node
snipping bot on pancake swap with node version


## Pre Purchase Checks
1. Listen for new contracts and 'liquidity add' events
2. Check contract is verified [configuable feature on/off]
3. Check if contract is honeypot (does it allow trading buy/sell) [configuable feature on/off]
4. Check for minting flag in contract code [configuable feature on/off]
5. Check buy and sell tax limit (pass varible entered by user) [configuable feature on/off]
6. Check if owner is renounced [configuable feature on/off] (may slow entry into new contract?)
7. Check if Liquidity Pool is Locked [configuable feature on/off] (may slow entry into new contract?)
8. Purchase amount based on percentage of L.P add OR purchase set amount of BNB (predefined by user varible).
9. Sell percentage of tokens/position (predefined user varible) if 
⦁ certain percentage profit is reached (predefined user varible) OR
⦁ sell if maximum hold time is reached in seconds, OR
⦁ sell if contract creator unlocks token (or similar possible scam event triggers in contract)

Usage
======================

1. first have to deploy smart contract (flashloan.sol) to mainnet(if deploy to test net  please check provider address and token address)
2. install Dapp's enviroments(node_module) 
```
$ npm install
```
3. run dapp
```
$ node index.js

```

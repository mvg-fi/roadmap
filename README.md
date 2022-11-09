# Roadmap


## todolist 

1. deploy and test multiple pools

Stableswap:

- [ ] USDT-ERC20 & USDT-TRC20 & pUSD & USDC

TriCrypto:

base:BTC,ETH,XIN,USDT,USDC,pUSD

- [ ] BTC & ETH & XIN & USDT
- [ ] BTC & BOX
- [ ] BTC & EOS
...

Write a script to deploy all the pools

Deploy a factory & registry for front-end


2. design a interface

- feature page
- swap
- pools
- my liquidity
- overview

- mobile version using mvm router


Possible problems:
- Routing
- How to show lp token in messenger (discuss)


features:

v1:
- Based on mvm, backed by smart contract
- Open source, proven to be secure
- Support single coin liquidity

v2:
- The most advanced AMM
- Concentrated liquidity
- More efficient, higher return than Uniswap v3
- Support single coin liquidity

### Test pools

4pool Stableswap: 0xF3F2ba723Da3BB6536CA9F2C5221Baf91247E5bE

tricrypto: 0x67b818876bDde6EFd3004549E9a792e1def779c1

## Interface

1. Swap page
- [x] Asset selector
- [x] Slippage setting
- [x] Connect wallet UI
- [x] Connect wallet error handling
- [x] Connect wallet state, determine connected (by provider)
- [ ] Fetch info from provider
- [ ] Output dynamic value
- [ ] Account detail drop down
- [ ] Calculate exchange rate, slippage(price impact), route
- [ ] Make all dialog able to close by clicking the overlay
- [ ] Add a swap detail dropdown

 1. If route is ok
	- Swap is not available
 2. If InputAmount is valid
	- Invalid amount
 3. Fetch from provider (get_dy)
 4. Show info of the trade
 5. Check if enough balance, check if enough gas fee
	- Insufficient balance
	- Insufficient ETH for gas
 6. Check if approved
	- Show approve btn

 How to get routes?
 1. input(x,y) address
 2. get each (poolId,poolData) by getting all pools 
 3. get all (coins(wrapped,underlying,meta),coinIndex) of the pool
 4. loop wrapped_coin.length, 


2. Pool page
- [ ] Add liquidity
- [ ] Remove liquidity
- [ ] Show all liquidity

3. Overall
- [ ] Account widget
- [ ] Switch network widget
- [ ] Overall UI
- [ ] Toast
- [x] I18n issue
- [ ] Dark mode
- [ ] Footer
- [ ] Typography

TODO:
- [x] Select asset button on:click transition and border
- [x] Wallet selector
- [ ] Figure out how to make routing works


Due date: 11.10

## Roadmap

- [ ] AMM
- [ ] DAO
- [ ] Derivatives
- [ ] MTG Service
- [ ] etc..

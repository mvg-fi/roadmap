# Roadmap

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
- Open source， proven to be secure
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
- [ ] Asset selector
- [ ] Connect wallet selector
- [ ] Slippage setting
- [ ] Fetch info from provider
- [ ] Calculate exchange rate, slippage(price impact), route
- [ ] Output dynamic value

2. Pool page
- [ ] WIP

3. Overall
- [ ] Dark mode
- [ ] i18n
- [ ] Footer

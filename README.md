# Create Binance Smart Chain Token

This is a basic tutorial with source code originally from Eat the Blocks blockchain tutorial series. Check out his projects @ <https://github.com/jklepatch/eattheblocks>

## Overview

This is the basic solidity token creation contract. You can change the max supply and add anything you'd like to this as it is skeleton and what most Meme coins use. 

## Steps

- Open new project @ <https://remix.ethereum.org/>
- Add Token.sol with source code
- Compile project _verify that the compiler is the same version in the Token.sol_
- Deploy with Injected Web 3 Environment
- *IMPORTANT* Do not navigate away you need to wait for blocks to commit AND transfer tokens to YOUR wallet
  -  fill in transfer field syntax: WALLETaccount#, # (Ex. 0xa3F07675B6663925D5092Eb32977A12DF1a3C037, 10000)
  -  verify transaction after 1min+ @ <https://bscscan.com/> with your Wallet Account Number
-  Listing on Pancake Swap
  -  Add Liquidity for trading _Recommend: BNB / NewToken for Pair_
  -  For the NewToken you need to paste the CONTRACT address
-  Done!

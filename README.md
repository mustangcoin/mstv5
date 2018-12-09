### Mustang Coin Official Development Repository

## Specifications

- Blockchain Name: Mustang Coin
- Ticker: MST
- PoW Algorithm: X11
- Name: Mustang Coin
- Short Name: MST
- Type: Hybrid to full PoS
- nStakeMinAge = 24 * 60 * 60; // 24 hours
- nStakeMaxAge = 30 * 24 * 60 * 60; // 30 days
- Coin supply: 3000000 MST
- Premine: None

## Chain Parameters:

- nTargetSpacing = 1 * 60;
- nModifierInterval = 10 * 60;
- nCoinbaseMaturity = 40;
- DAILY_BLOCKCOUNT = 1440;
- MAX_BLOCK_SIZE = 2000000;
- MIN_TX_FEE = 100000;
- (Last POW block: 17280)
- nSubsidy = nCoinAge * nRewardCoinYear / 365 / COIN;

## Sample mustang.conf file:

- rpcuser=UserName
- rpcpassword=YourSaltishPassworld
- rpcport=19666
- port=19668
- daemon=1
- server=1
- listen=1
- rpcallowip=127.0.0.1

- addnode=seed.mustangcoin.xyz
- addnode=seed02.mustangcoin.xyz
- addnode=seed03.mustangcoin.xyz

## Wallets:

- http://mustangcoin.xyz/#services

## Blockchain Explorers:

- https://chainz.cryptoid.info/mst/
- http://chains.sye.host/mst/index.php

## Peers/Nodes and Blockchain Stats 

- https://www.coinexchange.io/network/peers/MST
- http://chains.sye.host/mstnode/

## Exchnages:

- https://yobit.net/en/trade/MST/BTC
- https://www.coinexchange.io/market/MST/BTC

## Shop:

- http://mustangcoin.xyz/#shop

## Social Contacts:

- https://mustangcoin.xyz/
- https://twitter.com/mustangcoin
- https://bitcointalk.org/index.php?topic=1609008.0

## Repo Guidelines

- Developers work in their own forks, then submit pull requests when they think their feature or bug fix is ready.
- If it is a simple/trivial/non-controversial change, then one of the development team members simply pulls it.
- If it is a more complicated or potentially controversial change, then the change may be discussed in the pull request, or the        requester may be asked to start a discussion for a broader community discussion.
- The patch will be accepted if there is broad consensus that it is a good thing. Developers should expect to rework and resubmit patches if they don't match the project's coding conventions or are controversial.
- From time to time a pull request will become outdated. If this occurs, and the pull is no longer automatically mergeable; a comment on the pull will be used to issue a warning of closure. Pull requests closed in this manner will have their corresponding issue labeled 'stagnant'.


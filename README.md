# Introduction

Tradecoin (TRADE) is an open-source Proof-of-Stake digital crypto currency for
fast (using SwiftX), private (Zerocoin protocol) and secure microtransactions.
Our main goal is to create a decentralized fully secure and anonymous network
to run applications which do not rely on any central body control. By having a
distributed system, thousands of users will be responsible for maintaining the
application and data so that there is no single point of failure.

Tradecoin Cloud is a service-hosting platform. It provides a complete automated
solution to run fully managed and highly available multi-redundant Masternode
as a Service (MaaS) and Proof-of-Stake as a Service (PoSaaS). It is a simple
solution, manageable by anybody without any crypto currency knowledge. While
market competitors require local wallet installation, it is not necessary in
Tradecoin Cloud. You can run masternodes from local wallets, cloud wallets, paper
wallets, web wallets or mobile wallets. While this is more challenging task
from infrastructure and security point of view, it will improve mainstream
adoption and knowledge of masternodes. Adding new crypto currencies to the
platform does not require any manual intervention, neither from the currency
project team nor from the Tradecoin team. This processprocess is automated and new
crypto currencies work in sandbox mode for some period until verification
completed. Linux containers (LXC) manages isolation of different users and
their wallets. The verification process and using securely isolated containers
eliminates potential security breaches if crypto currency include backdoors to
withdraw foreign wallets. Beside Masternode as a Service (MaaS) and
Proof-of-Stake as a Service (PoSaaS) we implement Block Explorer as a Service
(BEaaS). It will significantly reduce service time to delivery for any new
crypto currency as we will deploy, run and maintain the block explorer. The
project and development teams can sharpen their focus on more important tasks.

# Coin Specifications

* Coin Name: Tradecoin
* Coin Ticker: TRADE
* Hash Algo: Quark
* RPC Port: 55886
* P2P Port: 55885
* Type: PoW / PoS / MN
* Minimum Staking Age: 2 Hours
* Rewards (till block 1500): MN 60%, PoW 40%
* Rewards (till block 205000): MN 60%, PoS 40%
* Rewards (from block 205001): MN 70%, PoS 30%
* Last PoW Block: 1.500
* Max Coin Supply: 25.000.000
* Masternode Collateral: 15.000
* Community Donation Address: https://explorer.tradecoin.team/address/UUr5nDmykhun1HWM7mJAqLVeLzoGtx19dX

# Proof-of-Work Rewards

Proof-of-Work is used as instamine protection and will end at block 1500.

Block Height   | Reward                 | MN  | PoW | Supply  | Runtime | Stage End
---------------|------------------------|-----|-----|---------|---------|-----------
Block 1        | 220.000 TRADE (premine) | 60% | 40% | 220.000 | 0 days  | 2018-05-25
Block 2 - 1500 |       1 TRADE           | 60% | 40% | 221.499 | 1 day   | 2018-05-26

# Proof-of-Stake Rewards

Proof-of-Stake will start at block 1501 until max coin emission is reached.

Stages   | Block Height    | Reward   | MN  | PoS | Supply     | Runtime  | Stage End
---------|-----------------|----------|-----|-----|------------|----------|-----------
Stage 1  |      1501-12000 | 100 TRADE | 60% | 40% |  1.271.399 |   7 days | 2018-06-02
Stage 2  |     12001-22000 |  90 TRADE | 60% | 40% |  2.171.309 |   7 days | 2018-06-09
Stage 3  |     22001-42000 |  80 TRADE | 60% | 40% |  3.771.229 |  14 days | 2018-06-23
Stage 4  |    42001-100000 |  70 TRADE | 60% | 40% |  7.831.159 |  40 days | 2018-08-02
Stage 5  |   100001-160000 |  60 TRADE | 60% | 40% | 11.431.099 |  42 days | 2018-09-13
Stage 6  |   160001-205000 |  50 TRADE | 60% | 40% | 13.681.049 |  31 days | 2018-10-14
Stage 7  |   205001-250000 |  25 TRADE | 70% | 30% | 14.806.024 |  31 days | 2018-11-14
Stage 8  |   250001-340000 |  15 TRADE | 70% | 30% | 16.156.009 |  62 days | 2019-01-15
Stage 9  |   340001-430000 |  10 TRADE | 70% | 30% | 17.055.999 |  62 days | 2019-03-18
Stage 10 |   430001-956000 |   5 TRADE | 70% | 30% | 19.685.994 | 365 days | 2020-03-17
Stage 11 |  956001-1482000 |   4 TRADE | 70% | 30% | 21.789.990 | 365 days | 2021-03-17
Stage 12 | 1482001-2008000 |   3 TRADE | 70% | 30% | 23.367.987 | 365 days | 2022-03-17
Stage 13 | 2008001-2534000 |   2 TRADE | 70% | 30% | 24.419.985 | 365 days | 2023-03-17
Stage 14 | 2534001-3114016 |   1 TRADE | 70% | 30% | 25.000.000 | 403 days | 2024-04-23

# Official Links

Website: https://tradecoin.team/

GitHub (Wallet): https://github.com/Tradecoin-Project/tradecoin/

GitHub (Project): https://github.com/Tradecoin-Project/

Block Explorer: https://explorer.tradecoin.team/

BitcoinTalk Announcement: https://bitcointalk.org/index.php?topic=4238243

Twitter: https://twitter.com/TradecoinEN

Discord: https://discord.tradecoin.team

Know Your Developer (KYD): https://review.kydcoin.io/tradecoin/

# Exchanges

Graviex: https://graviex.net/markets/tradebtc

# Promotions

Masternodes.online: https://masternodes.online/currencies/TRADE/

Coinlib.io: https://coinlib.io/coin/TRADE/Tradecoin

MNtop: https://mntop.co.in/

mnode.club: https://mnode.club/g/info/TRADE

Beam: https://beam.works/user/tradecoin/

Satoshi Solutions: https://satoshisolutions.online/

Chopcoin.io: https://trade.chopcoin.io/

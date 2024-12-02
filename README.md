# TranSurfCoin
[![N|Solid](https://avatars.githubusercontent.com/u/93602818?v=4)](https://transurfcoin.org)
=====================================

https://transurfcoin.org

What is TranSurfCoin?
----------------

TranSurfCoin is an experimental digital asset currency that enables instantly transfer digital asset as 
payments to anyone, anywhere in the world. TSC uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing coins are carried
out collectively by the network. TranSurfCoin Core is the name of open source
software which enables the use of this crypotocurrency.

## WhitePaper

You can read the [Transurfcoin Whitepaper](Transurfcoin_Whitepaper.pdf) for detailed information about project's vision and mission.


License
-------
TranSurfCoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Blockchain Explorer
-------
TranSurfCoin Community can check the transparent ledger at official blockchain explorer http://137.184.41.199:3001

### Coin Specs
| **Coin Head**               | **Value**        |
|-----------------------------|------------------|
| Ticker                      | TSC       |
| Average Block Time                  | 60 Seconds       |
| Hashing Algorithm           | SHA-256       |
| Max Coin Supply             | 750 000 000 TSC |
| Premine                     | 37 500 000 TSC  |
| P2P Port                    | 44664   |
| RPC Port                    | 44667  |


# Block Reward Schedule

TSC block reward is halved every **3,750,000 blocks**.

| **Block Range**        | **Reward (per Block)** | **Description**                              |
|-------------------------|------------------------|----------------------------------------------|
| 0                      | `0 * COIN`            | Genesis Block                                |
| 1                      | `37,500,000 * COIN`   | Premine                                      |
| 2 to 3,749,999         | `100 * COIN`          | Initial block rewards before first halving   |
| 3,750,000 to 7,499,999 | `50 * COIN`           | First halving                                |
| 7,500,000 to 11,249,999| `25 * COIN`           | Second halving                               |
| 11,250,000 to 14,999,999| `12.5 * COIN`         | Third halving                                |
| 15,000,000 to 18,749,999| `6.25 * COIN`         | Fourth halving                               |
| 18,750,000 onwards     | Reward halves every `3,750,000` blocks until it becomes `0`. |
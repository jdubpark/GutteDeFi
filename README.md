# A Collection of DeFi Attack Cases

Various Attacks on Decentralized Finance, where the term "Post-Mortem" is an acceptable(?) norm

**Last Update: June 30, 2021**

*** note that "Exploited/Lost" often calculates the value of lost tokens based on their exchange rate at the time of exploit (many times, exploits include numerous tokens so presenting the total loss in USD is easier to comprehend the extent of loss)

Similar compilation:

- [OpenBlockSec](https://github.com/openblocksec/blocksec-incidents/blob/main/defi/2021.md)
- [OpenZeppelin Post-Mortems](https://forum.openzeppelin.com/t/list-of-ethereum-smart-contracts-post-mortems/1191)
- rekt.news also provides good explanations on most hacks

| Targeted Protocol                  | Exploited/Lost                              | Post-Mortem                                                  | Analysis                                                     |
| ---------------------------------- | ------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **[Jun 2021]**                     |                                             |                                                              |                                                              |
| Visor Finance                      | $500k                                       | [Official](https://visorfinance.medium.com/visor-beta-incident-report-1b2521b9266) |                                                              |
| Impossible Finance                 | $500k                                       | [Official](https://medium.com/impossiblefinance/impossible-finance-v2-swap-jun-21st-postmortem-94e4b59ad490) | [Knownsec](https://medium.com/@Knownsec_Blockchain_Lab/one-thought-of-heaven-one-thought-of-hell-impossible-finance-lightning-loan-attack-incident-dd7b921a174c) |
| PancakeHunny                       | $86k                                        | [Official](https://medium.com/pancakehunny/pancakehunny-preliminary-incident-report-6da18bc3c0e6) |                                                              |
|                                    |                                             |                                                              |                                                              |
| **[May 2021]**                     |                                             |                                                              |                                                              |
| PancakeBunny                       | $45 mln                                     | [Official](https://pancakebunny.medium.com/hello-bunny-fam-a7bf0c7a07ba) | [cmichel](https://cmichel.io/bsc-pancake-bunny-exploit-post-mortem/) |
| Venus Protocol                     | $200 mln liqudated<br />+ $100 mln bad loan | [Official](https://medium.com/autofarm-network/21-april-2021-venus-vaults-post-mortem-1518ae7399c6) | [Igamberdiev](https://twitter.com/FrankResearcher/status/1394900186435096578) |
| Burgerswap                         | $7.2 mln                                    | [Decrypt](https://decrypt.co/72194/burgerswap-explains-7-2-million-flash-loan-attack-in-post-mortem?utm_source=reddit&utm_medium=social&utm_campaign=sm) |                                                              |
| bVaults (bEarn Finance)            | $11 mln                                     | [Official](https://bearn-defi.medium.com/bvaults-busd-alpaca-strategy-exploit-post-mortem-and-bearn-s-compensation-plan-b0b38c3b5540) |                                                              |
| Bogged Finance                     | $3.6 mln                                    | [Peckshield](https://peckshield.medium.com/bogged-finance-incident-root-cause-analysis-718d53faad5c) |                                                              |
| Belt Finance                       | $50 mln                                     | [Official](https://medium.com/belt-finance/may-29-incident-report-865d20cc46ca) | [Knownsec](https://medium.com/@Knownsec_Blockchain_Lab/knownsec-blockchain-lab-belt-finance-attack-event-analysis-b0ba64b100bd), [rekt](https://rekt.news/belt-rekt/) |
| xBNTa & xSNXa (xToken)             | $24.5 mln                                   | [Official](https://medium.com/xtoken/initial-report-on-xbnta-xsnxa-exploit-d6e784387f8e) |                                                              |
| Spartan Protocol                   | $40+ mln                                    | [Official](https://spartanprotocol.medium.com/today-spartan-protocol-was-subject-to-an-exploit-targeting-the-liquidity-pools-8589b2069cef) | [rekt](https://rekt.news/spartan-rekt/)                      |
| Rari Capital                       | 2600 ETH                                    | [Official](https://medium.com/rari-capital/5-8-2021-rari-ethereum-pool-post-mortem-60aab6a6f8f9) |                                                              |
| Value DeFi [3]                     | $11 mln <br />[total $28mln]                | gave up?                                                     | [rekt](https://www.rekt.news/value-rekt3/)                   |
| Value DeFi [2]                     | $10 mln                                     | [Official](https://medium.com/valuedefi/vstake-pool-incident-post-mortem-4550407c9714) | [rekt](https://www.rekt.news/value-rekt2/)                   |
| VaultSX                            | $13.5 mln                                   | [Official](https://www.eosgo.io/news/vaultsx-hack-lessnos-learned-and-thoughts) | [cmichel](https://cmichel.io/eos-vault-sx-hack/)             |
| SafeDollar                         | $250k                                       | [Official](https://safedollar.medium.com/safedollar-post-mortem-analysis-cb2769fe059) |                                                              |
| JulSwap                            | $700k                                       | [Official](https://justliquidity.medium.com/flash-loan-farming-julb-bnb-14c6c128f5dd) |                                                              |
|                                    |                                             |                                                              |                                                              |
| **[Apr 2021]**                     |                                             |                                                              |                                                              |
| Uranium Finance                    | $50 mln                                     | [Official (Wayback)](http://web.archive.org/web/20210428115141/https://uraniumfinance.medium.com/uranium-post-mortem-v2-compensations-aac4b0706d7d) | [CertiK](https://medium.com/certik-foundation/uranium-finance-exploit-analysis-d135055d6a6a) |
| EasyFi                             | $80 mln                                     | [Official (Wayback)](http://web.archive.org/web/20210420195832/https://medium.com/easify-network/easyfi-security-incident-pre-post-mortem-33f2942016e9) | [Halborn](https://halborn.com/explained-the-easyfi-hack-april-2021/) |
| Polkatrian                         | $3 mln                                      | [Official Response](https://polkatrain-com.gitbook.io/polkatrian-en/the-response-for-hacker-attack-incident-from-polkatrain-team) |                                                              |
| xFORCE (Force DAO)                 | 183 ETH (+ white hack)                      | [Official](https://blog.forcedao.com/xforce-exploit-post-mortem-7fa9dcba2ac3?gi=88e4af807a2) |                                                              |
|                                    |                                             |                                                              |                                                              |
| **[Mar 2021]**                     |                                             |                                                              |                                                              |
| DODO Pool                          | $3.8 mln                                    | [Official](https://medium.com/dodoex/dodo-pool-incident-postmortem-with-a-little-help-from-our-friends-327e66872d42) |                                                              |
| Social Money (Roll)                | 2857 ETH                                    |                                                              | [rekt](https://www.rekt.news/roll-rekt/)                     |
| PAID Network                       | $160 mln                                    | [Official](https://paidnetwork.medium.com/paid-network-attack-postmortem-march-7-2021-9e4c0fef0e07) |                                                              |
|                                    |                                             |                                                              |                                                              |
| **[Feb 2021]**                     |                                             |                                                              |                                                              |
| Alpha Homora <br />(Cream Finance) | $37.5 mln                                   | [Official](https://blog.alphafinance.io/alpha-homora-v2-post-mortem/) |                                                              |
| Furucombo                          | $15 mln                                     | [Official](https://medium.com/furucombo/furucombo-post-mortem-march-2021-ad19afd415e) |                                                              |
| Yearn Finance (v1 yDAI)            | 11 mln DAI                                  | [Official](https://github.com/yearn/yearn-security/blob/master/disclosures/2021-02-04.md) |                                                              |
| BT Finance                         | $1.7 mln                                    | [Official](https://btfinance.medium.com/bt-finance-exploit-analysis-report-a0843cb03b28) |                                                              |
| Growth DeFi (rAAVE)                | $1.3 mln                                    | [Official](https://growthdefi.medium.com/raave-farming-contract-exploit-explained-f3b6f0b3c1b3) | [rekt](https://www.rekt.news/the-big-combo/)                 |
|                                    |                                             |                                                              |                                                              |
| **[Jan 2021]**                     |                                             |                                                              |                                                              |
| yCredit Finance                    | $11 mln                                     |                                                              | [BlockSec](https://blocksecteam.medium.com/deposit-less-get-more-ycredit-attack-details-f589f71674c3), [banteng](https://github.com/banteg/exploit-ycredit) |
| Saddle Finance                     | 7.9 BTC                                     | [Official](https://medium.com/saddle/update-on-saddle-launch-cb5de01fa504) | [rekt](https://www.rekt.news/saddle-finance-rekt/)           |
|                                    |                                             |                                                              |                                                              |
| **[END OF 2020]**                  | **[END OF 2020]**                           | **[END OF 2020]**                                            | **[END OF 2020]**                                            |
|                                    |                                             |                                                              |                                                              |
| **[Dec 2020]**                     |                                             |                                                              |                                                              |
| Cover Protocol                     | $5 mln + $\alpha$                           | [Official](https://coverprotocol.medium.com/12-28-post-mortem-34c5f9f718d4) |                                                              |
| Warp Finance                       | $7.7 mln                                    | [Official](https://warpfinance.medium.com/warp-finance-exploit-summary-recovery-of-funds-5b8fe4a11898) | [SlowMist](https://slowmist.medium.com/analysis-of-warp-finance-hacked-incident-cb12a1af74cc) |
|                                    |                                             |                                                              |                                                              |
| **[Nov 2020]**                     |                                             |                                                              |                                                              |
| Value DeFi [1]                     | $7 mln                                      | [Official](https://valuedefi.medium.com/multistables-vault-exploit-post-mortem-d11b0635788f) | [rekt](https://www.rekt.news/value-defi-rekt/)               |
| Origin Protocol (OUSD)             | $7 mln                                      | [Official](https://blog.originprotocol.com/urgent-ousd-has-hacked-and-there-has-been-a-loss-of-funds-7b8c4a7d534c) |                                                              |
| Pickle Finance                     | $19 mln                                     | [Official](https://picklefinance.medium.com/pickle-was-hacked-and-there-has-been-a-loss-of-funds-414b99969c29) | [Banteg](https://github.com/banteg/evil-jar/blob/master/readme.md), [rekt](https://www.rekt.news/pickle-finance-rekt/) |
| Compound                           | $103 mln liquidated                         |                                                              | [Bitcoin.com](https://news.bitcoin.com/100-million-liquidated-on-defi-protocol-compound-following-oracle-exploit/) |
| Akropolis                          | 2 mln DAI                                   | [Official](https://akropolis.substack.com/p/delphi-savings-pool-exploit) |                                                              |
| SushiSwap                          | $150k                                       |                                                              | [SlowMist](https://slowmist.medium.com/slowmist-a-brief-analysis-of-the-story-of-the-sushi-swap-attack-c7bc6709adea) |
|                                    |                                             |                                                              |                                                              |
| **[Oct 2020]**                     |                                             |                                                              |                                                              |
| Harvest Finance                    | $33.8 mln                                   | [Official](https://medium.com/harvest-finance/harvest-flashloan-economic-attack-post-mortem-3cf900d65217) | [TheBlock](https://www.theblockcrypto.com/post/82292/defi-protocol-harvest-finance-exploited) |
|                                    |                                             |                                                              |                                                              |
| **[Sep 2020]**                     |                                             |                                                              |                                                              |
| SushiSwap                          | $13.8 mln (price crash)                     | [Chef Nomi](https://twitter.com/NomiChef/status/1304442495342796800) | [ZDNet](https://www.zdnet.com/article/defi-sushiswap-creator-returns-14m-in-eth-after-causing-coin-crash/) |
| SYFI                               | $300k                                       |                                                              |                                                              |
| iToken (bZx)                       | $8.1 mln (returned)                         | [Official](https://bzx.network/blog/incident)                |                                                              |
| Eminence Finance                   | $15 mln                                     |                                                              | [rekt](https://www.rekt.news/eminence-rekt-in-prod/)         |
|                                    |                                             |                                                              |                                                              |
| **[Aug 2020]**                     |                                             |                                                              |                                                              |
| Chainlink                          | 700 ETH (spam attack)                       |                                                              | [CryptoBriefing](https://cryptobriefing.com/chainlink-endures-spam-attack-congestion-high-fees/) |
| Opyn Protocol                      | $370k                                       | [Official](https://medium.com/opyn/opyn-eth-put-exploit-post-mortem-1a009e3347a8) | [PeckShield](https://blog.peckshield.com/2020/08/05/opyn/)   |
|                                    |                                             |                                                              |                                                              |
| **[Jun 2020]**                     |                                             |                                                              |                                                              |
| Balancer Protocol                  | $500k                                       | [Official](https://medium.com/balancer-protocol/incident-with-non-standard-erc20-deflationary-tokens-95a0f6d46dea) |                                                              |
|                                    |                                             |                                                              |                                                              |
| **[Apr 2020]**                     |                                             |                                                              |                                                              |
| LendF.me                           | $25 mln                                     |                                                              | [PeckShield](https://peckshield.medium.com/uniswap-lendf-me-hacks-root-cause-and-loss-analysis-50f3263dcc09) |
| imBTC Uniswap Pool                 | $300k                                       |                                                              |                                                              |
|                                    |                                             |                                                              |                                                              |
| **[Mar 2020]**                     |                                             |                                                              |                                                              |
| MakerDAO                           | $9 mln                                      | [Official](https://blog.makerdao.com/the-market-collapse-of-march-12-2020-how-it-impacted-makerdao/) | [Blocknative](https://www.blocknative.com/blog/mempool-forensics) |
|                                    |                                             |                                                              |                                                              |
| **[Feb 2020]**                     |                                             |                                                              |                                                              |
| bZx                                | 4698.02 ETH                                 | [Official](https://bzx.network/blog/postmortem-ethdenver)    | [PeckShield](https://peckshield.medium.com/bzx-hack-full-disclosure-with-detailed-profit-analysis-e6b1fa9b18fc), [palkeo](https://www.palkeo.com/en/projets/ethereum/bzx.html) |
|                                    |                                             |                                                              |                                                              |
| **[END OF 2019]**                  | **[END OF 2019]**                           | **[END OF 2019]**                                            | **[END OF 2019]**                                            |
|                                    |                                             |                                                              |                                                              |
| **[Dec 2019]**                     |                                             |                                                              |                                                              |
| Synthetix                          | $2.5 mln                                    |                                                              | [TheBlock](https://www.theblockcrypto.com/daily/57620/a-post-mortem-how-market-manipulation-left-synthetix-stakers-with-over-1m-in-debt) |
|                                    |                                             |                                                              |                                                              |
| **[Jun 2019]**                     |                                             |                                                              |                                                              |
| Synthetix                          | 37 mln sETH <br />($74 bln @ $2,000/sETH)   |                                                              | [TheBlock](https://www.theblockcrypto.com/linked/28748/synthetix-suffers-oracle-attack-potentially-looting-37-million-synthetic-ether) |



### Trivial & Unannounced

| Targeted Protocol             | Chain | Exploited/Lost | Post-Mortem                                                  | Analysis |
| ----------------------------- | ----- | -------------- | ------------------------------------------------------------ | -------- |
| Andre Cronje of yearn.finance |       | $562k          | [Andre Cronje](https://andrecronje.medium.com/post-mortem-28-02-2020-6d675a85a33b) |          |



### Exit Scams (Rug Pulls) & Bank Runs

| Targeted Protocol    | Type      | Exploited/Lost             | Post-Mortem                                                  | Analysis                                                     |
| -------------------- | --------- | -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **[June 2021]**      |           |                            |                                                              |                                                              |
| Iron Finance & TITAN | Bank-run  | $2 bln<br />(+ Mark Cuban) | [Official](https://ironfinance.medium.com/iron-finance-post-mortem-17-june-2021-6a4e9ccf23f5) | [rekt](https://www.rekt.news/iron-finance-rekt/), [Jeiwan](https://jeiwan.net/posts/analysis-titan-fall/) |
|                      |           |                            |                                                              |                                                              |
| **[Nov 2020]**       |           |                            |                                                              |                                                              |
| Sharktron            | Exit Scam | $10 mln                    |                                                              |                                                              |



### Rug Puts??

| Targeted Protocol | Exploited/Lost | Post-Mortem                                                  | Analysis                                                     | Note                                              |
| ----------------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------- |
| **[Jun 2021]**    |                |                                                              |                                                              |                                                   |
| Alchemix          | $6.5 mln       | [Official 1](https://forum.alchemix.fi/public/d/137-incident-report-06162021), [Official 2](https://alchemixfi.medium.com/alchemix-farm-migration-post-mortem-and-aleth-update-78c6dd98e3f5) | [SlowMist](https://slowmist.medium.com/slowmist-alchemix-hack-analysis-e8c9ec6c2ee3), [rekt](https://www.rekt.news/alchemix-rekt/) | Reward calcultion error,<br />users received more |
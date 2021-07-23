# A Collection of DeFi Attack Cases

Various Attacks on Decentralized Finance, where the term "Post-Mortem" is an acceptable(?) norm

*Similar compilation*: [OpenBlockSec](https://github.com/openblocksec/blocksec-incidents/blob/main/defi/2021.md); [OpenZeppelin Post-Mortems](https://forum.openzeppelin.com/t/list-of-ethereum-smart-contracts-post-mortems/1191); [rekt.news](); [Halborn](https://halborn.com/category/explained-hacks/)

[Interesting Hack Loss Leaderboard](https://www.rekt.news/leaderboard/) (from rekt.news)



#### Table of Content

- [DeFi Attacks](#attacks)
- [Exit Scams (Rug Pulls) & Bank Runs](#exits)
- [Trivial & Unannounced](#trivial)



** *Exploited/Lost* calculates the lost value based on exchange rate at the time. Many times, the loss is presented in USD value since multiple tokens are lost.

** Any Loss over **$10 million or 5000 ETH is bolded** (calculated at $2000 per ETH)

** Some Post-Mortems are taken down after being released, so the links may not always work (in such case, use Wayback).



## DeFi Attacks<a id="attacks"></a>

**Last Update: July 23, 2021**

| Date | Targeted Protocol                  | Exploited/Lost                                       | Post-Mortem                                                  | Analysis                                                     |
| ---- | ---------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ——   | **[END OF 2021]**                  | ——                                                   | ——                                                           | ——                                                           |
|      | TOTAL LOSS (so far)                | *~ **$660 mln*** <br />+ ***$300 mln*** Venus        |                                                              |                                                              |
| ——   | **[Jul 2021]**                     | ——                                                   | ——                                                           | ——                                                           |
| 22nd | THORChain (2nd)                    | $800k ($8 mln hacked, <br />white hacker 10%)        | [Official Twitter](https://twitter.com/THORChain/status/1418360746329608195) |                                                              |
| 16th | PancakeBunny (2nd)                 | $2.1 mln                                             | [Official](https://pancakebunny.medium.com/polybunny-post-mortem-compensation-42b5c35ce957) |                                                              |
| 15th | BONDLY (MantraDAO)                 | **$22 mln**                                          | [Official](https://medium.com/mantra-dao/bondly-exploit-how-it-unfolded-on-zenterest-postmortem-d8120d8d784b) |                                                              |
|      | THORChain                          | $5 mln (4000 ETH - slippage)                         | [Twitter](https://twitter.com/THORChain/status/1415899790043271171) |                                                              |
| 11th | ChainSwap (2nd)                    | $4 mln                                               | [Official](https://chain-swap.medium.com/chainswap-exploit-11-july-2021-post-mortem-6e4e346e5a32) |                                                              |
| 10th | AnySwap                            | $7.9 mln                                             | [Official](https://anyswap.medium.com/anyswap-multichain-router-v3-exploit-statement-6833f1b7e6fb) |                                                              |
| 2nd  | ChainSwap (1st)                    | $800k                                                | [Official](https://chain-swap.medium.com/chainswap-post-mortem-and-compensation-plan-90cad50898ab) |                                                              |
|      |                                    | *TOTAL $40 mln*                                      |                                                              |                                                              |
| ——   | **[Jun 2021]**                     | ——                                                   | ——                                                           | ——                                                           |
| 29th | Merlin Labs (3th)                  | $330k<br />[total $1.6 mln]                          | gone?                                                        | [PeckShield](https://twitter.com/peckshield/status/1409808532040343558), [rekt](https://www.rekt.news/merlin3-rekt/) |
| 28th | SafeDollar                         | $250k                                                | [Official](https://safedollar.medium.com/safedollar-post-mortem-analysis-cb2769fe059) |                                                              |
| 23th | Eleven Finance (NRV)               | $4.5 mln                                             | [Official](https://elevenfinance.medium.com/eleven-finance-nrv-vault-exploit-and-loss-of-funds-a-post-mortem-437a79ded743) |                                                              |
| 21st | Impossible Finance                 | $500k                                                | [Official](https://medium.com/impossiblefinance/impossible-finance-v2-swap-jun-21st-postmortem-94e4b59ad490) | [Knownsec](https://medium.com/@Knownsec_Blockchain_Lab/one-thought-of-heaven-one-thought-of-hell-impossible-finance-lightning-loan-attack-incident-dd7b921a174c) |
| 19th | Visor Finance                      | $500k                                                | [Official](https://visorfinance.medium.com/visor-beta-incident-report-1b2521b9266) |                                                              |
| 3rd  | PancakeHunny                       | $86k                                                 | [Official](https://medium.com/pancakehunny/pancakehunny-preliminary-incident-report-6da18bc3c0e6) |                                                              |
|      |                                    | *TOTAL $6 mln*                                       |                                                              |                                                              |
| ——   | **[May 2021]**                     | ——                                                   | ——                                                           | ——                                                           |
| 30th | Belt Finance                       | **$50 mln**                                          | [Official](https://medium.com/belt-finance/may-29-incident-report-865d20cc46ca) | [Knownsec](https://medium.com/@Knownsec_Blockchain_Lab/knownsec-blockchain-lab-belt-finance-attack-event-analysis-b0ba64b100bd), [rekt](https://rekt.news/belt-rekt/) |
| 28th | Burgerswap                         | $7.2 mln                                             | [Decrypt](https://decrypt.co/72194/burgerswap-explains-7-2-million-flash-loan-attack-in-post-mortem?utm_source=reddit&utm_medium=social&utm_campaign=sm) |                                                              |
|      | JulSwap                            | $700k                                                | [Official](https://justliquidity.medium.com/flash-loan-farming-julb-bnb-14c6c128f5dd) |                                                              |
| 27th | Merlin Labs (2nd)                  | 200+ ETH                                             |                                                              | [rekt](https://rekt.news/merlin2-rekt/)                      |
| 26th | Merlin Labs  (1st)                 | $680k                                                | [Official](https://merlinlab.medium.com/our-road-ahead-fa2fafc8167d) | [rekt](https://rekt.news/merlinlabs-rekt/)                   |
| 24th | Bogged Finance                     | $3.6 mln                                             | [Peckshield](https://peckshield.medium.com/bogged-finance-incident-root-cause-analysis-718d53faad5c) |                                                              |
| 20th | PancakeBunny                       | **$45 mln**                                          | [Official](https://pancakebunny.medium.com/hello-bunny-fam-a7bf0c7a07ba) | [cmichel](https://cmichel.io/bsc-pancake-bunny-exploit-post-mortem/) |
| 19th | Venus Protocol                     | **$200 mln liquidated**<br />**+ $100 mln bad loan** | [Official](https://medium.com/autofarm-network/21-april-2021-venus-vaults-post-mortem-1518ae7399c6) | [Igamberdiev](https://twitter.com/FrankResearcher/status/1394900186435096578) |
| 16th | VaultSX                            | **$13.5 mln**                                        | [Official](https://www.eosgo.io/news/vaultsx-hack-lessnos-learned-and-thoughts) | [cmichel](https://cmichel.io/eos-vault-sx-hack/)             |
|      | bVaults (bEarn)                    | **$11 mln**                                          | [Official](https://bearn-defi.medium.com/bvaults-busd-alpaca-strategy-exploit-post-mortem-and-bearn-s-compensation-plan-b0b38c3b5540) |                                                              |
| 12th | xBNTa & xSNXa (xToken)             | **$24.5 mln**                                        | [Official](https://medium.com/xtoken/initial-report-on-xbnta-xsnxa-exploit-d6e784387f8e) |                                                              |
| 8th  | Rari Capital                       | 2600 ETH                                             | [Official](https://medium.com/rari-capital/5-8-2021-rari-ethereum-pool-post-mortem-60aab6a6f8f9) |                                                              |
| 7th  | Value DeFi [2nd]                   | **$10 mln**                                          | [Official](https://medium.com/valuedefi/vstake-pool-incident-post-mortem-4550407c9714) | [rekt](https://www.rekt.news/value-rekt2/)                   |
| 5th  | Value DeFi [3rd]                   | **$11 mln <br />[total $28mln]**                     | gave up?                                                     | [rekt](https://www.rekt.news/value-rekt3/)                   |
| 2nd  | Spartan Protocol                   | **$40+ mln**                                         | [Official](https://spartanprotocol.medium.com/today-spartan-protocol-was-subject-to-an-exploit-targeting-the-liquidity-pools-8589b2069cef) | [rekt](https://rekt.news/spartan-rekt/)                      |
|      |                                    | *TOTAL **$233 mln***<br />+ ***$300 mln*** Venus     |                                                              |                                                              |
| ——   | **[Apr 2021]**                     | ——                                                   | ——                                                           | ——                                                           |
| 28th | Uranium Finance                    | **$50 mln**                                          | [Official (Wayback)](http://web.archive.org/web/20210428115141/https://uraniumfinance.medium.com/uranium-post-mortem-v2-compensations-aac4b0706d7d) | [CertiK](https://medium.com/certik-foundation/uranium-finance-exploit-analysis-d135055d6a6a) |
| 20th | EasyFi                             | **$80 mln**                                          | [Official (Wayback)](http://web.archive.org/web/20210420195832/https://medium.com/easify-network/easyfi-security-incident-pre-post-mortem-33f2942016e9) | [Halborn](https://halborn.com/explained-the-easyfi-hack-april-2021/) |
| 5th  | Polkatrian                         | $3 mln                                               | [Official Response](https://polkatrain-com.gitbook.io/polkatrian-en/the-response-for-hacker-attack-incident-from-polkatrain-team) |                                                              |
| 4th  | xFORCE (Force DAO)                 | 183 ETH (+ white hack)                               | [Official](https://blog.forcedao.com/xforce-exploit-post-mortem-7fa9dcba2ac3?gi=88e4af807a2) |                                                              |
|      |                                    | *TOTAL **$133 mln***                                 |                                                              |                                                              |
| ——   | **[Mar 2021]**                     | ——                                                   | ——                                                           | ——                                                           |
| 14th | Social Money (Roll)                | 2857 ETH                                             |                                                              | [rekt](https://www.rekt.news/roll-rekt/)                     |
| 9th  | DODO Pool                          | $3.8 mln                                             | [Official](https://medium.com/dodoex/dodo-pool-incident-postmortem-with-a-little-help-from-our-friends-327e66872d42) |                                                              |
| 5th  | PAID Network                       | **$160 mln**                                         | [Official](https://paidnetwork.medium.com/paid-network-attack-postmortem-march-7-2021-9e4c0fef0e07) | [Halborn](https://halborn.com/explained-the-paid-network-hack-march-2021/) |
|      |                                    | *TOTAL **$170 mln***                                 |                                                              |                                                              |
| ——   | **[Feb 2021]**                     | ——                                                   | ——                                                           | ——                                                           |
| 27th | Furucombo                          | **$15 mln**                                          | [Official](https://medium.com/furucombo/furucombo-post-mortem-march-2021-ad19afd415e) |                                                              |
| 13th | Alpha Homora <br />(Cream Finance) | **$37.5 mln**                                        | [Official](https://blog.alphafinance.io/alpha-homora-v2-post-mortem/) |                                                              |
| 8th  | BT Finance                         | $1.7 mln                                             | [Official](https://btfinance.medium.com/bt-finance-exploit-analysis-report-a0843cb03b28) |                                                              |
|      | Growth DeFi (rAAVE)                | $1.3 mln                                             | [Official](https://growthdefi.medium.com/raave-farming-contract-exploit-explained-f3b6f0b3c1b3) | [rekt](https://www.rekt.news/the-big-combo/)                 |
| 4th  | Yearn (v1 yDAI)                    | **11 mln DAI**                                       | [Official](https://github.com/yearn/yearn-security/blob/master/disclosures/2021-02-04.md) |                                                              |
|      |                                    | *TOTAL **$66.5 mln***                                |                                                              |                                                              |
| ——   | **[Jan 2021]**                     | ——                                                   | ——                                                           | ——                                                           |
| 19th | Saddle Finance                     | 7.9 BTC (slippage)                                   | [Official](https://medium.com/saddle/update-on-saddle-launch-cb5de01fa504) | [rekt](https://www.rekt.news/saddle-finance-rekt/)           |
| 2th  | yCredit Finance                    | **$11 mln**                                          |                                                              | [BlockSec](https://blocksecteam.medium.com/deposit-less-get-more-ycredit-attack-details-f589f71674c3), [banteng](https://github.com/banteg/exploit-ycredit) |
|      |                                    | *TOTAL **$11 mln***                                  |                                                              |                                                              |
|      |                                    |                                                      |                                                              |                                                              |
| ——   | **[END OF 2020]**                  | ——                                                   | ——                                                           | ——                                                           |
|      | TOTAL LOSS                         | ~ ***$158 mln***<br />+ ***$103 mln*** Compound      |                                                              |                                                              |
| ——   | **[Dec 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 28th | Cover Protocol                     | $5 mln + more                                        | [Official](https://coverprotocol.medium.com/12-28-post-mortem-34c5f9f718d4) |                                                              |
| 17th | Warp Finance                       | $7.7 mln                                             | [Official](https://warpfinance.medium.com/warp-finance-exploit-summary-recovery-of-funds-5b8fe4a11898) | [SlowMist](https://slowmist.medium.com/analysis-of-warp-finance-hacked-incident-cb12a1af74cc) |
|      |                                    | *TOTAL **$13.7 mln***                                |                                                              |                                                              |
| ——   | **[Nov 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 30th | SushiSwap                          | $150k                                                |                                                              | [SlowMist](https://slowmist.medium.com/slowmist-a-brief-analysis-of-the-story-of-the-sushi-swap-attack-c7bc6709adea) |
| 27th | Compound                           | **$103 mln liquidated**                              |                                                              | [Bitcoin.com](https://news.bitcoin.com/100-million-liquidated-on-defi-protocol-compound-following-oracle-exploit/) |
| 22th | Pickle Finance                     | **$19 mln**                                          | [Official](https://picklefinance.medium.com/pickle-was-hacked-and-there-has-been-a-loss-of-funds-414b99969c29) | [Banteg](https://github.com/banteg/evil-jar/blob/master/readme.md), [rekt](https://www.rekt.news/pickle-finance-rekt/) |
| 17th | Origin Protocol (OUSD)             | $7 mln                                               | [Official](https://blog.originprotocol.com/urgent-ousd-has-hacked-and-there-has-been-a-loss-of-funds-7b8c4a7d534c) |                                                              |
| 14th | Value DeFi [1st]                   | $7 mln                                               | [Official](https://valuedefi.medium.com/multistables-vault-exploit-post-mortem-d11b0635788f) | [rekt](https://www.rekt.news/value-defi-rekt/)               |
| 12th | Akropolis                          | 2 mln DAI                                            | [Official](https://akropolis.substack.com/p/delphi-savings-pool-exploit) |                                                              |
|      |                                    | *TOTAL **$35.1 mln***<br />+ ***$103 mln*** Compound |                                                              |                                                              |
| ——   | **[Oct 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 26th | Harvest Finance                    | **$33.8 mln**                                        | [Official](https://medium.com/harvest-finance/harvest-flashloan-economic-attack-post-mortem-3cf900d65217) | [TheBlock](https://www.theblockcrypto.com/post/82292/defi-protocol-harvest-finance-exploited) |
|      |                                    | *TOTAL **$33.8 mln***                                |                                                              |                                                              |
| ——   | **[Sep 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 29th | Eminence Finance                   | **$15 mln**                                          |                                                              | [rekt](https://www.rekt.news/eminence-rekt-in-prod/)         |
| 15th | iToken (bZx)                       | $8.1 mln (returned)                                  | [Official](https://bzx.network/blog/incident)                |                                                              |
| 11th | SushiSwap                          | **$13.8 mln (price crash)**                          | [Chef Nomi](https://twitter.com/NomiChef/status/1304442495342796800) | [ZDNet](https://www.zdnet.com/article/defi-sushiswap-creator-returns-14m-in-eth-after-causing-coin-crash/) |
| ??   | SYFI                               | $300k                                                |                                                              |                                                              |
|      |                                    | *TOTAL **$29 mln***                                  |                                                              |                                                              |
| ——   | **[Aug 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 30th | Chainlink                          | 700 ETH (spam attack)                                |                                                              | [CryptoBriefing](https://cryptobriefing.com/chainlink-endures-spam-attack-congestion-high-fees/) |
| 10th | Opyn Protocol                      | $370k                                                | [Official](https://medium.com/opyn/opyn-eth-put-exploit-post-mortem-1a009e3347a8) | [PeckShield](https://blog.peckshield.com/2020/08/05/opyn/)   |
|      |                                    | *TOTAL $1.8 mln*                                     |                                                              |                                                              |
| ——   | **[Jun 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 28th | Balancer Protocol                  | $500k                                                | [Official](https://medium.com/balancer-protocol/incident-with-non-standard-erc20-deflationary-tokens-95a0f6d46dea) |                                                              |
|      |                                    | *TOTAL $0.5 mln*                                     |                                                              |                                                              |
| ——   | **[Apr 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 18th | LendF.me                           | **$25 mln**                                          |                                                              | [PeckShield](https://peckshield.medium.com/uniswap-lendf-me-hacks-root-cause-and-loss-analysis-50f3263dcc09) |
|      | imBTC Uniswap Pool                 | $300k                                                |                                                              | [pNetwork](https://medium.com/pnetwork/is-a-new-token-standard-really-to-blame-for-the-imbtc-uniswap-and-dforce-attacks-31c62e2bc799), [DeFi Rate](https://defirate.com/imbtc-uniswap-hack/) |
|      |                                    | *TOTAL **$25.3 mln***                                |                                                              |                                                              |
| ——   | **[Mar 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 12th | MakerDAO                           | $9 mln                                               | [Official](https://blog.makerdao.com/the-market-collapse-of-march-12-2020-how-it-impacted-makerdao/) | [Blocknative](https://www.blocknative.com/blog/mempool-forensics) |
|      |                                    | *TOTAL $9 mln*                                       |                                                              |                                                              |
| ——   | **[Feb 2020]**                     | ——                                                   | ——                                                           | ——                                                           |
| 17th | bZx                                | 4698.02 ETH                                          | [Official](https://bzx.network/blog/postmortem-ethdenver)    | [PeckShield](https://peckshield.medium.com/bzx-hack-full-disclosure-with-detailed-profit-analysis-e6b1fa9b18fc), [palkeo](https://www.palkeo.com/en/projets/ethereum/bzx.html) |
|      |                                    | *TOTAL $9.4 mln*                                     |                                                              |                                                              |
|      |                                    |                                                      |                                                              |                                                              |
| ——   | **[END OF 2019]**                  | ——                                                   | ——                                                           | ——                                                           |
|      | *TOTAL LOSS*                       | ~ ***$2.5 mln***                                     |                                                              |                                                              |
| ——   | **[Dec 2019]**                     | ——                                                   | ——                                                           | ——                                                           |
| 26th | Synthetix                          | $2.5 mln                                             |                                                              | [TheBlock](https://www.theblockcrypto.com/daily/57620/a-post-mortem-how-market-manipulation-left-synthetix-stakers-with-over-1m-in-debt) |
|      |                                    | *TOTAL **$2.5 mln***                                 |                                                              |                                                              |
| ——   | **[Jun 2019]**                     | ——                                                   | ——                                                           | ——                                                           |
| 24th | Synthetix                          | **37 mln sETH <br />($74 bln @ $2,000/sETH)**        |                                                              | [TheBlock](https://www.theblockcrypto.com/linked/28748/synthetix-suffers-oracle-attack-potentially-looting-37-million-synthetic-ether), [Etherscan](https://etherscan.io/tx/0x93819f6bbea390d7709fa033f5733d16418674e99c43b9ed23adb4110d657f0c) |
|      |                                    | *TOTAL **$74 bln***                                  |                                                              |                                                              |



## Exit Scams (Rug Pulls) & Bank Runs<a id="exits"></a>

**Last Update: June 30, 2021**

| Date | Targeted Protocol        | Exploited/Lost                 | Analysis                                                     | Note                                                         |
| ---- | ------------------------ | ------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|      | **[June 2021]**          |                                |                                                              |                                                              |
| 24th | **StableMagnet**         | **$27 mln**                    | [bsc.news](https://www.bsc.news/post/stablemagnet-and-others-rugpull-22m-in-stablecoin-through-unverified-swap-code) |                                                              |
| 16th | **Iron Finance & TITAN** | **$2 bln**<br />(+ Mark Cuban) | [rekt](https://www.rekt.news/iron-finance-rekt/), [Jeiwan](https://jeiwan.net/posts/analysis-titan-fall/) | **Bank-run**<br />[Official Post-Mortem](https://ironfinance.medium.com/iron-finance-post-mortem-17-june-2021-6a4e9ccf23f5) |
|      |                          |                                |                                                              |                                                              |
|      | **[May 2021]**           |                                |                                                              |                                                              |
| 24th | **DeFi100**              | **$32 mln**                    |                                                              |                                                              |
|      |                          |                                |                                                              |                                                              |
|      | **[Nov 2020]**           |                                |                                                              |                                                              |
| 10th | **Sharktron**            | **$10 mln**                    | [Bitcoin.com](https://news.bitcoin.com/sharktron-defi-project-devs-exit-scam-tron-foundation-says-part-of-missing-funds-now-frozen/) |                                                              |

#### Rug Puts??

| Date | Targeted Protocol | Exploited/Lost | Post-Mortem                                                  | Analysis                                                     | Note                                              |
| ---- | ----------------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------- |
|      | **[Jun 2021]**    |                |                                                              |                                                              |                                                   |
| 21st | Alchemix          | $6.5 mln       | [Official 1](https://forum.alchemix.fi/public/d/137-incident-report-06162021), [Official 2](https://alchemixfi.medium.com/alchemix-farm-migration-post-mortem-and-aleth-update-78c6dd98e3f5) | [SlowMist](https://slowmist.medium.com/slowmist-alchemix-hack-analysis-e8c9ec6c2ee3), [rekt](https://www.rekt.news/alchemix-rekt/) | Reward calcultion error,<br />users received more |



## Trivial & Unannounced<a id="trivial"></a>

| Date | Targeted Protocol             | Chain | Exploited/Lost | Post-Mortem                                                  | Analysis |
| ---- | ----------------------------- | ----- | -------------- | ------------------------------------------------------------ | -------- |
|      | [Feb 2020]                    |       |                |                                                              |          |
| 27th | Andre Cronje of yearn.finance |       | $562k          | [Andre Cronje](https://andrecronje.medium.com/post-mortem-28-02-2020-6d675a85a33b) |          |


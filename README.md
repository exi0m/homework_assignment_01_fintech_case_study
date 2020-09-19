![MakerDao](https://miro.medium.com/proxy/1*t716v7cBXEseyVe6-6VySg.jpeg)
# Do Or Dai

## Overview and Origin
### The Engine Behind the DeFi Train, MakerDAO

* Name of the company? **MakerDAO**
* When was the company incorporated? **2014**
* Who are the founders of the company? **Rune Christensen**
* How did the idea for the company (or project) come about? **Wanted to the first to build a stablecoin built on the Ethereum blockchain**
* How is the company funded? How much funding have they received? **Venture capital funding. Has had 5 rounds, totaling $27M and Andreessen Horowitz being a lead investor. Also the Maker Foundation holds an unaccounted number of MKR tokens(their governance token) of liquidity, which also gets sold to VC funds. One example is selling $27.5M of MKR tokens to VC funds Dragonfly Capital Partners and Paradigm. Currently holds $250M valuation**

## Business Activities
Rune's first introduction of MakerDAO can be found in [this Reddit post](https://www.reddit.com/r/ethereum/comments/30f98i/introducing_edollar_the_ultimate_stablecoin_built/)

* What specific financial problem is the company or project trying to solve? **First you have to understand what is "Maker" and what is "DAO". "Maker" stands for "Market Maker", which was an idea based upon BitUSD's inability to attract market makers, which eventually led to the lack of liqudity. It was originally intended to distribute "MKR" to certain crypto market makers to ensure their was incentive in the system and boost liquidity. "DAO"("Decentralized Autonomous Organization") means there is no central entity to govern MakerDAO's business decisions. MakerDAO has three differnet subcategories that make up the ecosystem: 1) A decentralized lending platform 2) a governance token, MKR and 3) DAI, it's stablecoin.**

* Who is the company's intended customer?  Is there any information about the market size of this set of customers?
What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?) **Originally the intended audience was for those looking to find a p2p lending solution(which is handling over $1B+ of collateral per day, WETH being the highest utility), but with the surge of DeFi, it has become those looking to use DAI as the standard as the stablecoin to handle DeFi investment.  

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.) **The system they use is built on the ethereum blockchain. Here's an explanation of each part of the MakerDAO system:** 

#### The Lending Platform
MakerDAO allows you to lend and borrow using their decentralized system. It cuts out the middle man, requesting a loan from national banks, credit unions, lenders, all usually with high APR rates. Collateral is required, just as you would with a bank, but with cryptocurrency. Currently the platform only accepts the Ethereum token and BAT(Other platforms allow you to use DAI as a source of collateral). The collateral is locked up to a smart contract called the collateralized debt position(CDP), in which then you will be returned DAI, it's stable coin. The collateral is locked up in the "Maker Vault", which is a component of the Maker Protocol, which generates the DAI against the CDP. DAI is destroyed once you repay off the generated DAI balance. This process happens entirely on-chain which allows full audibility of circulating DAI and the Collateral backing it. Vaults are required to be over-collateralized, meaning for every DAI, there's one or more dollars locked into CDP. No KYC process required either. Maker has also a feature called the Dai Savings Rate (DSR). DAI holders can lock their DAI into Maker’s DSR contract and earn a variable interest rate in DAI, which is generated from stability fees.

#### MKR 
The business and governance logic is codified within a smart contract system. Any new policies proposed must be made through smart contracts to the ethereum blockchain. Shareholders must hold MKR, MakerDAO's governance token, and must send MKR tokens to vote on proposals. Once the proposal is accepted, CDP(Collateralized Debt Position) will release DAI(MakerDAO's fully collateral-backed stablecoin currency which is pegged against the USD) against it.

#### DAI
The stablecoin inherits price predictability, being able to facilitate a number of financial activities. Some of it's use cases like hedging during periods of market instability, track price earnings with crypto-to-DAI pairing or capability to be used within custom derivative smart contracts.


#### How The System Depends On Each Other
Lending platform needs the stable coin(DAI) to function, DAI wouldn’t be stable without being over-collateralized. The system that allows over-collateralization of DAI is the lending platform. The crypto assets that back each DAI are supplied by users who lock them up in CDPs to take out loans. Which are all governed by MakerDAO’s shareholders who hold MKR governance tokens.

## Landscape:

* What domain of the financial industry is the company in? **P2P lending, Blockchain**

* What have been the major trends and innovations of this domain over the last 5-10 years? **DeFi** [Defirate.com/dai](https://defirate.com/dai/). **Dai, which has been titled the flagship of the DeFi trend, created the** [Migration Risk Construst Proposal](https://blog.makerdao.com/governance-poll-migration-risk-construct-proposal/) **which initiated the era of the DeFi movement. Prior, collateral for loans could only use Ether, but eventually including Basic Attention Token(BAT) and the** [Dai Savings Option](https://blog.makerdao.com/an-update-on-the-dai-savings-rate-in-multi-collateral-dai/) **which soon began to push the borders of what we now call decentralized financial services.**

* What are the other major companies in this domain? **Lending: Aave, Compound, Kava. Assets: WBTC, Ampleforth, TrueUSD, USD Coin, Paxos Standard**

## Results

* What has been the business impact of this company so far? **Because of their help in the DeFi world, the cryptocurrency world is reminiscent of 2017. The current amount of USD locked into DeFi as of September is $9.35B, with Maker locked with $1.1B**

* How is your company performing relative to competitors in the same domain? [DefiPulse.com](https://defipulse.com/) **It's considered the 3rd highest grossing company out of any DeFi project.**

## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!) **For the lending platform to introduce an assortment of cryptocurrency as a form of collateral. Even though Eth is accepted, you're subjected to only a set of two tokens, not even the coins that are created on the ethereum chain. It limits the possibility. Also insurance for collateral. This sets a precedence for a user to feel uneasy about anomalous events that could occur such as losing your wallet. Also a higher standard of smart contract auditing since they are subjected to errors as this is still an early language that still have hidden bugs and loopholes that create major risk. No issue has taken place yet within MakerDAO but this does not indicate future results and future DeFi products**


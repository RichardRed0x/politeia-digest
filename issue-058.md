# Politeia Digest #58 - March 17 - March 29 2023

![Image credit: @sænder](img/issue058/058-title.png)

**Treasury balance: 802,637 DCR (approx +7,969 DCR/month) - $18.1 million (+$170K/month) based on $21.31 DCR price**

## New Proposals

**[Change PoW/PoS Subsidy Split to 1/89 and Change PoW Algorithm to BLAKE3](https://proposals.decred.org/record/a8501bc)**

Published Mar 27 by jy-p | 43 comments

This proposal is about making some changes to the consensus rules: changing the PoW algorithm to BLAKE3 (thus rendering all existing Decred ASICs useless) and changing the subsidy split to 1/89, reducing the PoW share of rewards to 1%. The subsidy split change is an accentuation of a previous [change](https://proposals.decred.org/record/427e1d4) which already saw a 60/30 split in favour of miners switch to 10/80 in favour of PoS ticket voters. The change of PoW algorithm would ensure that the existing miners, including the "malicious mining cartel" which is being targeted by this proposal, lose their dominance of the PoW aspect of consensus and the associated rewards. The proposed drop to 1% of rewards for PoW is intended to make the development of new ASICs or equivalent for Decred unprofitable, and therefore unlikely. The proposal references Monero's ASIC-resistance and RandomX but concludes that RandomX is too heavy for Decred's needs. The proposal requests a budget of $20,000 to implement the changes, and this work is estimated to take 2-4 weeks to complete, at which point the consensus upgrade/voting [process](https://docs.decred.org/proof-of-stake/overview/) could begin.

Many of the comments suggest redirecting the PoW subsidy to the Treasury rather than PoS rewards. There are also several comments asking for more information or reporting about the "continuing pattern" of malicious miner behaviour. Questions were also raised about whether related software (e.g. DCR PoW Pool and gominer) could or should be updated as part of the proposal, but these jobs are not covered.

**[Decrediton Ledger Support](https://proposals.decred.org/record/609db9e)**

Published Mar 27 by joegruff, last edited Mar 28 | 7 comments

This proposal requests a budget of $20,500 to integrate the Ledger hardware with Decrediton and allow users to send and receive DCR using a wallet stored on their Ledger device. This proposal does not include any work that would require firmware changes from Ledger, because it is deemed unlikely for these to be accepted within a reasonable timeframe - as a result it is limited to ordinary transactions and will not allow for PoS participation, because this requires message signing and that is not supported by the Ledger firmware presently. The proposed integration would only support standard transactions, so payments from TSpends or ticket votes would likely cause problems. The budget consists of $5,000 payment in arrears for work on a [proof of concept](https://github.com/JoeGruffins/ledger-decred-poc), $500 for 3 Ledger devices for developers to use, and $15,000 for the development work, which would be led and largely completed by @joegruff. The work is given an estimate of six months for completion, which is described as an overestimate to allow for merging bottlenecks.

The early comments are supportive of the proposal. @jz\_bz added some [context](https://proposals.decred.org/record/609db9e/comments/3) around the current state of Ledger integration and need for this work, the existing Ledger Live integration has proven to be unreliably maintained and frequently unusable, and so an integration with Decrediton will allow Decred users to bypass Live and use their hardware directly.

## Approved Proposals

**[Decred Journal and Politeia Digest 2023](https://proposals.decred.org/record/9e68dca)**

Published Mar 4 by bee, last edited Mar 6 | 11 comments

*Recap: This proposal requested a budget of $40,000 for 12 months of producing Decred Journal and Politeia Digest, with a 90/10 split in budget between these. Spending figures for the previous period were reported; the total spent was $25,570, which was 77% of the proposal's limit, and it was spent mostly on the Journal ($24,050) with only $1,520 spent on Politeia Digest (6%). It was a relatively quiet year for Politeia, with only 6 issues of PD being published in the 9 month period covered by the previous proposal. Some figures were reported for an average 2022 issue, ~4,400 words and 220 links to sources.*

**[Decred DEX - Desktop App and Packaging](https://proposals.decred.org/record/ae7c4fe)**

Published Mar 7 by buck54321 | 5 comments

*Recap: This proposal requested a budget of $29,000 to develop a more user-friendly Decred DEX installation package for desktop users (Windows, Mac and Linux). The work would be completed by the Decred DEX team with @buck54321 taking the lead, a proof of concept has been completed for Debian-based Linux which demonstrates using desktop notifications and the system tray to enhance user experience. The work is expected to take around 12 weeks of full-time equivalent work performed part-time in conjunction with the other Decred DEX efforts.*

**[Decred DEX - Client Development](https://proposals.decred.org/record/ca6b749)**

Published Mar 7 by buck54321 | 28 comments (+3)

*Recap: This proposal requested a budget of $182,000 to fund around 9 months of work on the Decred DEX client, with a focus on improving wallet functionality for all of the assets supported. Additional assets are being targeted for support, like Polygon and DigiByte, and the integrated wallet functionality will be improved for Zcash (to support shielded pools) and Decred (staking and mixing). The rationale for this refocus of development is that Decred DEX is the first point of contact many users have with Decred, they may not want or need a heavy duty wallet like Decrediton but could still benefit from some of Decred's advanced features through the built-in DEX wallet.*

**[Decred DEX - Market Maker and Arbitrage Bot Development](https://proposals.decred.org/record/8b1ceda)**

Published Mar 7 by martonp, last edited Mar 16 | 8 comments

*Recap: This proposal requests a budget of $73,000 for development of market making and arbitrage trading bots to work with Decred DEX, work is expected to take 9 months (with a limit of 14) and would be led by @martonp. The rationale for providing software to run these bots is that it would open up the prospect of acting as a market maker to many more users because they would not need to create their own bot first. Decred DEX markets would benefit from added liquidity provided by users running the market maker bots, and the arbitrage trading bot could be used to generate profits by exploiting and closing gaps between the DEX price and that on a CEX (initially Binance and Bittrex).*

## Rejected Proposals

**[Cointelegraph Content Proposal](https://proposals.decred.org/record/ff64137)**

Published Mar 4 by mattyleight, last edited Mar 13 | 56 comments (+1)

*Recap: This proposal requested $50,000 for a package of content to be published on Cointelegraph's website and other channels, with $25,000 to be paid up front before work begins and another $25,000 after the first month of collaboration - @exitus and @tivra are named as the Decred representatives who would facilitate the relationship. The content would be delivered over 4-6 weeks and include: one spotlight article and one interview article, each to be pinned on the main page for 24 hours, featured in the related news section and shared on Cointelegraph's Twitter and Telegram - and also a Twitter Spaces with live tweeting, and after talking to some community members on a livestream they decided to add a free press release, usually valued at $8,000. The budget is broken down into a main part of $47K, with an additional $3K classified as "volatility protection", effectively a surcharge for accepting DCR as payment.*

## About this issue

Content for this edition was authored by @richardred.

Image credit: @sænder

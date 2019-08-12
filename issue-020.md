# Politeia Digest #20 - August 1-12 2019

![Image credit: @30000fps](img/issue020/020-title.png)

**Treasury balance: 633,010 DCR (approx +14,836 DCR/month) - $17.3 million (+$405k/month) based on $27.35 DCR price**

### New proposals

**[Decentralized Exchange Development](https://proposals.decred.org/proposals/417607aaedff2942ff3701cdb4eff76637eca4ed7f7ba816e5c0bd2e971602e1)**

Published Aug 7 by chappjc, updated Aug 11 - 11 comments (+11)

This proposal requests a budget of $230,000 (largely labor costs) for developing the Decred Distributed Exchange (DEX). The work would be led by @chappjc and @buck545321 along with Company 0, and it would be run as an open source project where any approved contractor can bill the Treasury for their work on it.

The proposal provides a high level overview of the DEX server and client deliverables, these would be written in Go as command-line interface (CLI) programs. Future development projects would add a GUI for the client using the Electron Framework. The initial client will require full nodes for both blockchains (e.g. dcrd and btcd). The task is broken down into 7 milestones, with an estimated completion date before Q3 2020. The proposal was edited in response to a [comment](https://proposals.decred.org/proposals/417607aaedff2942ff3701cdb4eff76637eca4ed7f7ba816e5c0bd2e971602e1/comments/2) to provide full-time equivalent workload estimates for each milestone.

Comments on the proposal are generally supportive, with one [asking](https://proposals.decred.org/proposals/417607aaedff2942ff3701cdb4eff76637eca4ed7f7ba816e5c0bd2e971602e1/comments/3) about the differences to sparkswap.com and getting an in depth response.

### Market Makers

There have been three proposals submitted, on Aug 7, which offer market making services to Decred. The objective of these proposals would be to increase order book depth for DCR markets. DCR is often cited as having poor liquidity because there is little DCR available on exchanges in the form of orders on the books - as compared to other cryptocurrencies with similar market capitalization. Market makers would provide liquidity by maintaining buy and sell orders on selected markets, this would allow people who wished to buy or sell DCR to make larger orders without moving the price as much. One example that has been given is that selling as little as $5,000 worth of DCR can move the price down up to 5% - hindering the use of DCR as a medium of exchange.

For those new to market making, the difference between the offers relates to the number of markets/pairs/crosses covered, the amount of liquidity provided and how tight the spread is around the current price, and also how consistently the service will be maintained. In terms of pricing, the key difference is in how trading fees are handled, with some proposals charging these to the Treasury, while the Grapefruit proposal covers these within their fee.

Each market maker will require inventory (DCR, for Altonomy some BTC/USD as well), which a PoW miner has volunteered to provide), and the Treasury is being asked to pay an interest rate on this loan. The Grapefruit proposal mentions a rate of 0.8% per month to offset the opportunity cost of staking the DCR, but it seems that the same terms will be available to all 3 proposals.

All of the proposals are for initial terms of 6 months.

After three days of discussion on Politeia, in chats and on reddit, the main question being debated was whether Decred should pay for this kind of service at all. @jz submitted an RFP proposal on Aug 10 to establish whether there is support generally for hiring a market maker. If this proposal does not pass then the market maker proposals will not go up for a vote, if it passes then discussion can focus on whether to accept any of the offers on the table, and if so which one. This [gist](https://gist.github.com/RichardRed0x/1f905f51092c66326e1132d54ed00ef5) aims to maintain an up to date comparison of the three proposals, making estimates of their cost on the same basis, and noting any differences in how the offers are specified. The same information as of the time of this issue's snapshot is repeated below.

**[Altonomy - Market Making Proposal for Decred](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60)**

Published Aug 7 by runchen - 29 comments (+29)

This proposal is arguably the most expensive, it has lower monthly fees than i2 ($35k/month vs $40k/month) but a higher inventory requirement. This proposal also does not put a cap on trading fees, which would be charged to the Treasury. It offers coverage of the most pairs (10), with layered offers (looser spread than i2) of $50k up to 5% away from the current price. It offers the highest uptime guarantee (100%).

Altonomy is a well established trading, advisory and asset management firm and provides liquidity management services to 40+ of the top 200 cryptocurrencies by market cap.

Altonomy authorized their proposal to start voting within the first 24 hours of it being published, so they're obviously keen to get down to business.

**[i2 Trading: DCR Market Making](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9)**

Published Aug 7 by i2trading - 47 comments (+47)

This proposal offers the same liquidity per pair as Altonomy, with tighter spreads but fewer pairs (6) and lower uptime (90%). @max_bronstein made an interesting [comment](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156538382612762agSZH:decred.org?via=decred.org&via=matrix.org&via=zettaport.com) about this, suggesting that 100% uptime may not be as positive as it appears, as it would obligate the market maker to maintain their offer even during times when doing so is inconvenient and could cost them money.

Iterative Capital is an established presence in the Decred ecosystem, as an investment manager (with an excellent [thesis](https://iterative.capital/thesis/)) that is a large-scale Bitcoin and Decred miner, they are a significant stakeholder in the project. i2 also run the 4th largest VSP and a mining pool, and provide liquidity for DCR in the OTC markets through i2 trading. While i2 Trading has strong familiarity with the Decred ecosystem, they do not have the same degree of experience of providing market-making services as the other firms who made proposals.

**[Grapefruit Trading Market Making proposal](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b)**

Published Aug 7 by grapefruittrading - 30 comments (+30)

This proposal is the cheapest, the total liquidity on offer is lower ($30k each side on 4 pairs) and there are two options for how tight the spread is, with different costs. Grapefruit have framed their proposal in different terms to the others. 1% from each side of the current price in those proposals is equivalent to "2% wide bid-to-ask" in Grapefruit's proposal (this is the more expensive of their options). The difference in framing means that Grapefruit have freedom to offer bids or asks which are closer to the current price, at their discretion, as long as the spread between their bid and ask is <= 2%. Grapefruit's proposal does not describe layering of order depth which the other proposals would use. Grapefruit would guarantee 80% uptime.

Grapefruit Trading are a young firm, founded by Mike Komaransky, who has significant experience in this kind of business from Cumberland DRW.

The table below will be maintained in this [gist](https://gist.github.com/RichardRed0x/665f7640e74702032c931c4a494af841).

|                            | Altonomy               | i2 Trading               | Grapefruit tight      | Grapefruit loose      |
| -------------------------- | ---------------------- | ------------------------ | --------------------- | --------------------- |
| Liquidity (each side)      | $50k                   | $50k                     | $30k                  | $30k                  |
| Pairs                      | 10                     | 6                        | 4                     | 4                     |
| Total liquidity (e/s)      | $500k                  | $300k                    | $120k                 | $120k                 |
| Spread                     | $5k/1%,$20k/2%,$50k/5% | $10k/1%,$30k/2%,$50k/4%  | $30k 1% (flexible)    | $30k 2% (flexible)    |
| Uptime                     | 100%                   | 90%                      | 80%                   | 80%                   |
| Fees                       | $35k/m                 | $40k/m                   | $40k/m                | $28k/m                |
| Inventory                  | 30k DCR,700k USD/BTC   | 30k DCR                  | 12k DCR               | 12k DCR               |
| Interest                   | $85k                   | $43k                     | $17k                  | $17k                  |
| Monthly cost               | $49k                   | $47k                     | $43k                  | $31k                  |
| 6 month cost               | $295k                  | $283k                    | $257k                 | $185k                 |
| Trading fees               | Paid by Treasury       | Treasury (max 20k/month) | Included in price     | Included in price     |
| $ of liquidity per $ spent | $1.7 (+ fees)          | $1.06 (+ fees)           | $0.47 (includes fees) | $0.65 (includes fees) |

**[RFP: Decred Designated Market Maker](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd)**

Published Aug 10 by jz_bz last updated Aug 10 - 28 comments ()

This proposal asks the stakeholders to signal whether or not they want to hire a market maker - moving the process forward to considering which (if any) of the current proposals to choose, or dropping the idea entirely. @jz makes a case for approving the proposal and hiring a market maker, citing the improved user experience liquidity would bring and the problems illiquidity causes - it is one of the main barriers reported by large institutional players. As background, @jz notes that when he began the search for market makers in Jan 2018 there were none who were willing or able to participate in the kind of open proposal process Decred required, only over the course of the crypto winter have some firms opened up to the idea of making this kind of proposal. The proposal credits Max Bronstein and Chris Burniske as helping to set up the offers from the market makers, and explains what the market makers were asked to provide and the terms they are being asked to adopt.

If this proposal passes, the discourse around the market makers decision can proceed to the question of which option should be pursued (or how they should be adapted). If this proposal is rejected, the market maker proposals will not be put to a vote. @jz also stipulates that the deals offered by the market makers should have a total monthly cost (including interest and exchange fees) which does not exceed $60k per month, and that in the event that the proposal passes narrowly the market makers should consider scaling back their offer to a total cost of around $30k/month.

If the proposal passes, in order for a market maker proposal to be approved it will still have to meet the normal requirements, and have the most support (yes votes - no votes) of all 3 proposals.

### Proposals open for voting

**[TinyDecred: A Python Toolkit for Decred](https://proposals.decred.org/proposals/20e967dad9e7398901decf3cfe0acf4e0853f6558a62607265c63fe791b8b124)**

Published Jul 30 by buck54321 last updated Jul 30 - voting started on Aug 5 - 21 comments ()

Latest voting figures: 7,809 Yes votes, 781 No votes (90.9% Yes) - voter participation of 20.9%, support from 19% of tickets.

> Recap: This proposal requests $8,000 for work already completed on [TinyDecred](https://github.com/buck54321/tinydecred), a set of Python tools which enable Python developers to easily add support for Decred into their applications. @buck54321 has been a Decred contributor and contractor for a year working mostly on dcrdata, they developed TinyDecred as an unpaid learning exercise initially, but now think it has reached a point where it has value for the community, and request $8,000 for the work which went into it. Costs are predicated on more than 2 months of full-time work, at a substantial reduction to @buck54321's usual contractor hourly rate. If the proposal is approved, the TinyDecred repository will be moved to the Decred organization, and @buck54321 will continue to maintain it.

### Approved proposals

**[Decred Fundamental Metrics Research Proposal - Phase 1](https://proposals.decred.org/proposals/78b50f218106f5de40f9bd7f604b048da168f2afbec32c8662722b70d62e4d36) - voting finished Aug 6 - 19 comments ()**

10,630 Yes votes, 889 No votes (92.3% Yes) - voter participation of 28.4%, support from 26% of tickets.

### Other News

From Aug 1 until Aug 12 there were:

* 5 new proposals submitted, 1 proposals started voting, 1 proposals finished voting.
* Proposals that have finished voting have an average (mean) turnout of 28.4%, with a total of 11,519 ticket votes being cast.
* 160 comments on Politeia proposals from 18 different users.
* 405 up/down votes on comments from 18 different voting users.

## About this issue

Snapshot for this issue based on this [commit](https://github.com/decred-proposals/mainnet/commit/8726ece075a802c5301577a58e5fa2838e991ae8).

Content for this edition was authored by @richardred.

Image credit: @30000fps.

Also available on [medium]({}).

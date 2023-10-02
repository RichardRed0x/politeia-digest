# Politeia Digest #64 - August 27 - September 26 2023

![Image credit: @sænder](img/issue064/064-title.png)

**UPDATE (Sep 27)**: *Now with latest updates to the status of the Monde PR and Odaily proposals, and more detail about voting issues faced by the first Cake Wallet proposal.*

**Treasury balance: 827,167 DCR (approx +7,359 DCR/month) - $11.1 million (+$99K/month) based on $13.48 DCR price**

## New Proposals

**[Cake Wallet Integration Again](https://proposals.decred.org/record/b3bdacb)**

Published Sep 12 by joegruff | last edited Sep 13 | 6 comments

Meet the new Cake Wallet integration proposal, same as the old Cake Wallet integration [proposal](https://proposals.decred.org/record/2f25f2d) - which you may remember from the last issue, and can also find below in the Rejected Proposals section.

In what is a very rare outcome, the initial proposal for Cake Wallet integration failed to reach the quorum requirement of 20% of eligible tickets voting, it could only manage 18% turnout. There were however some unusual circumstances which led to the effective voting period being much shorter than the usual 7 days. After the activation of the PoW algorithm [consensus change](https://github.com/decred/dcps/blob/master/dcp-0011/dcp-0011.mediawiki) there was a period of almost 3 days with no blocks, of which 2 days overlapped with the proposal's [voting period](https://dcrdata.decred.org/proposal/2f25f2da17aa4007). During this period of no blocks being mined voting software [did not function normally](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$Q4g7SkmU07zBxyufYUdHi8jCbipCQLRPOYrBtxjTC_Y), preventing many votes from being cast (unless [setting back the clock](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$Up4fpmE77Xle4zfe1h1wKd9QlhTHhYxK1WRW_Ivvugk) and other workarounds were used). After block production has resumed several clients were not working for a couple of more days due to another [bug with syncing blocks](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$BCNsqoUfeOqYaVWIO7EUH3O14Kojns9Y5HiDvXa1VWg) which required restarting nodes. Then on September 2 no votes have been cast for 6 hours for either of the proposals being voted on, possibly a server issue. As if that were not enough, GPU mining kicked in during the last days of voting to produce blocks much faster than the average speed of 5 minutes per block. As a result the vote ended sooner than some people expected, because vote duration is based on block numbers and not on time.

Overall Cake Wallet's period of problem-free voting was reduced significantly, down to ~3.5 days according to [one estimate](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$3iVbKTZ_iGrQYKnNBszExCjfHP-LY5eYesu2wB6rJQY). On top of the issues caused by the hardfork, the start of Cake Wallet's voting was not grouped with another proposal which started a bit earlier (normally multiple proposals are started at the same time to maximize engagement) because it was not authorized at the time when the other proposal started voting, and also there has been almost no outreach on Twitter or Reddit to make voters aware of the proposal (again unlike the other proposals).

The original Cake Wallet Integration proposal was riding high with [87% approval](https://dcrdata.decred.org/proposal/2f25f2da17aa4007) and would definitely have been approved if the quorum had been met, even if all of the additional votes were No votes. This was probably the first proposal to fall into that crack which has long been [identified](https://blockcommons.red/publication/quorum-change-examples/) in this kind of quorum definition, a scenario where people who wish to see the proposal rejected may benefit from tactically delaying their vote if there is a chance that the proposal may fail on grounds of failing to meet the quorum requirement.

Considering the extremely rare interference with a hardfork and other factors, @joegruff was [encouraged](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$5jUX97uN0bew594frHrgkCiMtsCiZwZD51XCXzFiSDI) to submit the proposal again, and duly did so, with the substance of the proposal unchanged.

All of the comments are expressing support for the proposal except [one](https://proposals.decred.org/record/b3bdacb/comments/4) which asks if the maintainers have willingness and dev resources to merge changes in reasonable time, to which @joegruff responded that they have been punctual in communication so far but no promises can be given by him.

**[Decred PR Proposal Phase Five](https://proposals.decred.org/record/0c04c6f)**

Published Sep 15 by lindseymmc, last edited Sep 26 | 27 comments

This proposal requests $48,000 for another year of Public Relations provision at $4,000/month. @l1ndseymm has been providing these services to Decred for four years, and her last [proposal](https://proposals.decred.org/record/d5221a9) was approved with 66% support at a budget of $48,000. The proposal originally requested $60,000 because @l1ndseymm's team has been expanded to 5 to include "two crypto media relations experts and two support-level PRs" - the edit reduced the budget to the same as previous year and also introduced the new team members, likely in response to [comments](https://proposals.decred.org/record/0c04c6f/comments/20) on the proposal. The transition from solo outfit to structured team is expected to bring increased efficiency and result in better number and quality of media placements.

This proposal was almost withdrawn by @lindseymmc following some negative comments from people using alternate Politeia accounts "to protect from political blowback", and a perceived lack of recognition of the value of the PR work in the community. However, after [indicating](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$OEmunnF2PoOqeShWG-q6E0gx7P-3ycYVfJh8vCuyQ8k) her intention to abandon the proposal on Matrix @lindseymmc received more supportive comments from the community and encouragement to follow through with the vote, and she [decided](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$DaMHq-cvQxQxH8WNq3um20U4mINhLDZfzFI4LW8QIz8?via=decred.org&via=t2bot.io&via=matrix.org) to authorize voting after editing the proposal on Sep 26. 

## Proposals under discussion

**[Odaily Content Proposal](https://proposals.decred.org/record/b80040f)**

Published Aug 10 by conniej | 12 comments (+4)

This proposal requests $15,000 for the writing and publication of two articles about Decred over the span of a six month period during which the editors will be contactable. Odaily is a Chinese language crypto news site that claims 1.5 million unique monthly users. The content of the articles would be approved by a Decred representative, @Dominic, and metrics like number of pageviews would be shared after 2 weeks. The budget explicitly states that all $15,000 is for Odaily "content service budget" and @Dominic's reviewing budget is $0.

The comments ask questions about the nature of the content/relationship, and in some cases questioning the high price. [One](https://proposals.decred.org/record/b80040f/comments/3) of the comments highlighted Odaily's heavy promotion of Decred-Next, a fork which attempted to keep alive a version of the network which still paid miners 60% of rewards (i.e. without [DCP-10](https://github.com/decred/dcps/blob/master/dcp-0010/dcp-0010.mediawiki)) - and they promptly removed all of that content.

It has been over a month since the proposal was submitted and since @conniej responded to any comments, but the latest word from @dominic is that @conniej is busy at the moment and will return.

## Approved Proposals

**[Cryptopower: Golang Native Desktop & Mobile Wallet](https://proposals.decred.org/record/256efee)**

Published Aug 10 by dreacot | last edited Aug 21 | 30 comments (+3)

Final voting figures: 70% Yes votes, 62% turnout of eligible tickets.

*Recap: This proposal requested a budget of $61,600 to resurrect the GoDCR codebase and replace its former function as a desktop and mobile DCR wallet, but in this case also add support for BTC and LTC to become a multi asset wallet. GoDCR and the mobile wallets dcrandroid and dcrios have been discontinued since they [failed](https://proposals.decred.org/record/0ef42e5) to secure development funding. Prior to the submission of the proposal a [v1.0.0 release](https://github.com/crypto-power/cryptopower/releases/tag/release-v1.0.0) was put out with desktop apps for Linux, macOS and Windows, and an experimental Android APK build which is not yet stable. If this proposal is funded, Android and iOS versions of Cryptopower will be uploaded to the app stores and a range of new features will be developed including staking, voting, DCRDEX integration and coin control. The proposal includes a big table showing how Cryptopower compares to Decrediton, DCRDEX, Cake Wallet and the old mobile apps. The projected plan is for 28 weeks of full time equivalent work charged at $55/hr, with 10 weeks each projected for mobile enhancements and DCRDEX integration. The estimated delivery timeframe is 4-5 months. The proposal also includes a list of initiatives that didn't make the cut for this initial proposal but may well appear in future iterations, depending on community feedback.*

Cryptopower [proposal voting](https://dcrdata.decred.org/proposal/256efeee04b8145a) was also disrupted by the hardfork interference but to a much lesser degree than Cake Wallet. Cryptopower started voting earlier, had more bug-free voting time, and also was better supported in social media.

Note: It has been clarified to the Politeia Digest team by @dreacot that some of the features described above as "to be developed" were already complete, for clarity: staking, voting, coin control, BTC and LTC support were already usable and not part of the proposal.

## Rejected Proposals

**[Cake Wallet Integration](https://proposals.decred.org/record/2f25f2d)**

Published Aug 22 by joegruff | last edited Aug 24 | 6 comments (+5)

Final voting figures: 87% Yes votes, 18% turnout of eligible tickets.

Voting for this proposal was shorter than usual because of irregularities in the block production schedule following the activation of DCP-0011.

*Recap: This proposal requested a budget of $80,000 to add Decred support to Cake Wallet, the work would be completed by approved Decred developers and there would be no charge from Cake Wallet to integrate the support in their releases. There is a relevant [video](https://www.youtube.com/watch?v=0KKsD4ZhZn0) where @tivra and @phoenixgreen discuss the prospects for the relationship with a Cake Wallet representative. Cake Wallet is a popular multi asset wallet with a built in exchange function, it was mobile only until Feb 2023 and since then has desktop versions for Linux and MacOS. The Decred integration would be using SPV mode to process blocks directly on the device so no privacy-compromising third party is required, and the team have expressed a willingness to support other advanced features in future.*

## About this issue

Content for this edition was authored by @richardred with feedback from @dreacot and in depth voting problem research plus review from @bee.

Image credit: @sænder

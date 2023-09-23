# Politeia Digest #64 - August 27 - September 23 2023

![Image credit: @sænder](img/issue064/064-title.png)

**Treasury balance: 872,121 DCR (approx +7,359 DCR/month) - $11.4 million (+$96K/month) based on $13.09 DCR price**

## New Proposals

**[Cake Wallet Integration Again](https://proposals.decred.org/record/b3bdacb)**

Published Sep 12 by joegruff | 5 comments

Meet the new Cake Wallet integration proposal, same as the old Cake Wallet integration [proposal](https://proposals.decred.org/record/2f25f2d) - which you may remember from the last issue, and can also find below in the Rejected Proposals section. In what is a very rare outcome, the initial proposal for Cake Wallet integration failed to reach the quorum requirement of 20% of eligible tickets voting, it could only manage 18% turnout. There were however some unusual circumstances which led to the voting period being much shorter than the usual 7 days. After the activation of the PoW algorithm consensus change there was a period of almost 2 days with no blocks, followed by a period of several days of rapid block production as the difficulty adjustment took a massive step down - the Cake Wallet voting period overlapped with this and so the target block interval was met much more quickly than the usual 7 days under average speed of 5 minutes per block. The original Cake Wallet Integration proposal was riding high with 87% approval and would definitely have been approved if the quorum had been met, even if all of the additional votes were No votes. This was probably the first proposal to fall into that crack which has long been [identified](https://blockcommons.red/publication/quorum-change-examples/) in this kind of quorum definition, a scenario where people who wish to see the proposal rejected may benefit from tactically delaying their vote if there is a chance that the proposal may fail on grounds of failing to meet the quorum requirement. @joegruff was [encouraged](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$5jUX97uN0bew594frHrgkCiMtsCiZwZD51XCXzFiSDI?via=decred.org&via=t2bot.io&via=matrix.org) to submit the proposal again, and duly did so, with the substance of the proposal unchanged.

All of the comments are expressing support for the proposal except [one](https://proposals.decred.org/record/b3bdacb/comments/4) which asks if the maintainers have willingness and dev resources to merge changes in reasonable time, to which @joegruff responded that they have been punctual in communication so far but no promises can be given by him.

**[Decred PR Proposal Phase Five](https://proposals.decred.org/record/0c04c6f)**

Published Sep 15 by lindseymmc | 10 comments

This proposal requests $60,000 for another year of Public Relations provision at $5,000/month. @l1ndseymm has been providing these services to Decred for four years, and her last [proposal](https://proposals.decred.org/record/d5221a9) was approved with 66% support at a budget of $48,000. @l1ndseymm's team has been expanded to 5 (although not clear from what baseline) to include "two crypto media relations experts and two support-level PRs", which is expected to bolster media relations and result in larger media presence for Decred. 

4 of the comments are from @shane about specific messaging and outreach suggestions, the remaining comments ask questions about the new staff and there is [one](https://proposals.decred.org/record/0c04c6f/comments/9) very critical comment from what appears to be a self-disclosed alternate account "to protect from political blowback".

@Lindsey has [indicated](https://matrix.to/#/!qYpAAClAYrHaUIGkLs:decred.org/$OEmunnF2PoOqeShWG-q6E0gx7P-3ycYVfJh8vCuyQ8k?via=decred.org&via=t2bot.io&via=matrix.org) that she does not intend to progress to voting with the proposal, citing a lack of positive sentiment towards the PR work generally and recent hurtful comments. 

## Proposals under discussion

**[Odaily Content Proposal](https://proposals.decred.org/record/b80040f)**

Published Aug 10 by conniej | 11 comments (+3)

This proposal requests $15,000 for the writing and publication of two articles about Decred over the span of a six month period during which the editors will be contactable. Odaily is a Chinese language crypto news site that claims 1.5 million unique monthly users. The content of the articles would be approved by a Decred representative, @Dominic, and metrics like number of pageviews would be shared after 2 weeks. The budget explicitly states that all $15,000 is for Odaily "content service budget" and @Dominic's reviewing budget is $0, so it is not clear what Dominic is getting out of this arrangement.

The comments ask questions about the nature of the content/relationship, and in some cases questioning the high price. [One](https://proposals.decred.org/record/b80040f/comments/3) of the comments highlighted Odaily's heavy promotion of Decred-Next, a fork which attempted to keep alive a version of the network which still paid miners 60% of rewards - and they promptly removed all of that content. 

It has been over a month since the proposal was submitted and since @conniej responded to any comments, as the proposal is still not authorized for voting the spectre of abandonment looms large.

## Approved Proposals

**[Cryptopower: Golang Native Desktop & Mobile Wallet](https://proposals.decred.org/record/256efee)**

Published Aug 10 by dreacot | last edited Aug 21 | 27 comments

Final voting figures: 70% Yes votes, 62% turnout of eligible tickets.

*Recap: This proposal requested a budget of $61,600 to resurrect the GoDCR codebase and replace its former function as a desktop and mobile DCR wallet, but in this case also add support for BTC and LTC to become a multi asset wallet. GoDCR and the mobile wallets dcrandroid and dcrios have been discontinued since they [failed](https://proposals.decred.org/record/0ef42e5) to secure development funding. Prior to the submission of the proposal a [v1.0.0 release](https://github.com/crypto-power/cryptopower/releases/tag/release-v1.0.0) was put out with desktop apps for Linux, macOS and Windows, and an experimental Android APK build which is not yet stable. If this proposal is funded, Android and iOS versions of Cryptopower will be uploaded to the app stores and a range of new features will be developed including staking, voting, DCRDEX integration and coin control. The proposal includes a big table showing how Cryptopower compares to Decrediton, DCRDEX, Cake Wallet and the old mobile apps. The projected plan is for 28 weeks of full time equivalent work charged at $55/hr, with 10 weeks each projected for mobile enhancements and DCRDEX integration. The estimated delivery timeframe is 4-5 months. The proposal also includes a list of initiatives that didn't make the cut for this initial proposal but may well appear in future iterations, depending on community feedback.*

Note: It has been clarified to the PD team by @dreacot that some of the features described above as "to be developed" were already complete, for clarity: staking, voting, coin control, BTC and LTC support were already usable and not part of the proposal.

## Rejected Proposals

**[Cake Wallet Integration](https://proposals.decred.org/record/2f25f2d)**

Published Aug 22 by joegruff | last edited Aug 23 | 6 comments (+5)

Final voting figures: 95% Yes votes, 47% turnout of eligible tickets.

Voting for this proposal was shorter than usual because of irregularities in the block production schedule following the activation of DCP-0011.

*Recap: This proposal requested a budget of $80,000 to add Decred support to Cake Wallet, the work would be completed by approved Decred developers and there would be no charge from Cake Wallet to integrate the support in their releases. There is a relevant [video](https://www.youtube.com/watch?v=0KKsD4ZhZn0) where @tivra and @phoenixgreen discuss the prospects for the relationship with a Cake Wallet representative. Cake Wallet is a popular multi asset wallet with a built in exchange function, it was mobile only until Feb 2023 and since then has desktop versions for Linux and MacOS. The Decred integration would be using SPV mode to process blocks directly on the device so no privacy-compromising third party is required, and the team have expressed a willingness to support other advanced features in future.*

## About this issue

Content for this edition was authored by @richardred with review from @bee (hopefully).

Image credit: @sænder

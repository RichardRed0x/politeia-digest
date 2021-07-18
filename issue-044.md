# Politeia Digest #44 - June 19 - July 18 2021

![Image credit: @30000fps](img/issue044/044-title.png)

**Treasury balance: 698,260 DCR (approx + 10,634 DCR/month) - $79.1 million (+$1.2M/month) based on $113.33 DCR price**

## Proposals open for voting

**[Automatic Ticket Revocations Consensus Change](https://proposals.decred.org/record/e2d7b7d)**

Published Jul 6 by rstaudt | edited Jul 6 | 14 comments

Voting figures as of writing: 11,920 Yes votes, 330 No votes (97.3% Yes) - voter participation of 30%.

This proposal outlines a new consensus rules change, it projects costs of $10,000 to produce the code and DCP, to be drawn from the core network development budget. The purpose of this consensus change is to automate the ticket revocation process - this would simplify the user experience by obviating the need to revoke tickets manually. Additionally, this would be of significant benefit to the small number of tickets which are stuck in an unrevoked state - with the original Voting Service Provider (VSP) there was a redeem script which users needed to keep to redeem their tickets in a case where the VSP disappeared while tickets were unvoted, and the user had never voted any previous tickets with that VSP. According to a quick [report](https://github.com/rstaudt2/dcrd/blob/7aa2a239cf3748bef1402f615033b2c5c25ce779/unrevoked_ticket_stats.csv) produced by @rstaudt there are just under 2,000 tickets in this kind of unrevoked state. If implemented, this consensus change would make all future revocations automatic (miners would have to include these transactions for their blocks to be valid). A secondary step would see a script produced which performs a one-time revocation of all the legacy unrevoked tickets.

The comments on the proposal are supportive of this change, and include a detailed [one](https://proposals.decred.org/record/e2d7b7d/comments/5) from @davecgh which gives his review of the changes pros and cons in detail. The only downside identified in the proposal or comments relates to PoW miners, who will no longer receive fees for revocation transactions, but this is a positive for stakeholders who no longer need to pay such fees.

**[Twitter Bot Phase 1 @StakeShuffle_](https://proposals.decred.org/record/2895755)**

Published Jun 29 by coinshuffle_bot | edited Jul 5| 15 comments

Voting figures as of writing: 8,831 Yes votes, 1,103 No votes (88.9% Yes) - voter participation of 24%.

This proposal seeks retroactive funding for development of the [StakeShuffle Twitter Bot](https://twitter.com/StakeShuffle_) - a total of $2,240 for work completed so far (estimated to be around 280 hours). The proposal owner developed the bot after seeing requests from @thebochinchero and @checkmate for this kind of bot, it turned into a bigger job than they were expecting, and although they received some DCR tips initially these were deemed insufficient to support its continued development. If this proposal is approved, work will commence on Phase 2, incorporating a number of new metrics [suggested](https://proposals.decred.org/record/2895755/comments/4) by @checkmate, and a further proposal will then be submitted which requests reimbursement for this work.

Comments raised a number of issues which @coinshuffle_bot has responded to by editing the proposal - project was not on GitHub, no license, use of deprecated CoinShuffle branding, lack of detail on previous development effort and lack of clarity on future direction. Comments are also generally supportive of the proposal.

## New proposals

**[Daylight Robbery - Dominic Frisby Documentary Proposal](https://proposals.decred.org/record/ae609f1)**

Published Jul 16 by frizzers | edited Jul 18 | 60 comments

This proposal requests $300,000 (down from initial $495,000) to produce a 90-100 minute documentary film based on @frizzers' book "[Daylight Robbery](https://www.penguin.co.uk/books/309/309526/daylight-robbery/9780241360842.html)". Decred would be the "sponsor-advertiser and publisher-broadcaster" of the film, and the film would be released into the public domain with no copyright restrictions. The film would not feature Decred heavily but would reference it in a section on " future governance systems, private money and digital nomads". The proposal also introduces @frizzers' background as a comedian, voice actor and financial writer, and references a recently recorded [interview](https://youtu.be/ZCfIM8IHurU) with @jy-p. The proposal also introduces Alex Webster, who would be the editor and main collaborator on the project. Payments for the proposal are structured around 4 milestones - $150,000 covering pre-production and production, $150,000 for post-production and marketing (at this point whoever is reviewing the invoice can inspect the final product). The benefits to Decred are envisioned to result from major recognition of the film as "the first open-source DAO-funded documentary".

Some of the strongest criticism [comes](https://proposals.decred.org/record/ae609f1/comments/28) from @stately,plump, who claims to also have experience working in TV/Film - it accuses @frizzers of lying about a writing credit for Four Horsemen, misrepresenting his track record and that of the proposed director, and raises questions about the funding and distribution of his previous work and why samples are not available to review. This comment also casts @frizzers as a fringe personality who would not present Decred in a positive light to a general audience of prospective stakeholders. Most of the other comments are generally appreciative of @frizzers' previous work and instead take issue with the high cost (most comments relate to the initial $495K budget) and the lack of assurance that the documentary would have a suitable impact on Decred's recognition for this investment. Another theme of the comments is wanting the documentary to feature Decred more heavily. There are also community members who support the proposal in its current form, and some who have stated they are still considering it.

## Approved proposals

**[Decred Bug Bounty Program: Phase 4](https://proposals.decred.org/record/e1f104b)**

Published Jun 6 by degeri | edited Jun 7 | 8 comments (+0)

Final voting figures: 19,637 Yes votes, 304 No votes (98.5% Yes) - voter participation of 47%.

*Recap: This proposal requests a budget of $5,000 for maintenance of the program for another 1 year, with a maximum budget of $100,000 for bounty payouts. The payout amounts have been increased as compared to previous phases, to increase interest and participation. The proposal reported maintenance costs of $1,822 for the last year, in dealing with a total of 51 submissions, including 4 valid reports. Payouts for the 4 valid reports totalled $2,860. The proposal notes a number of challenges around getting quality submissions for high sensitivity software, and a few choppy interactions with bug submitters that can be improved upon in future.*

**[Explicit Version Upgrades Consensus Change](https://proposals.decred.org/record/3a98861)**

Published Jun 7 by davecgh | 20 comments (+1)

Final voting figures: 19,697 Yes votes, 13 No votes (99.9% Yes) - voter participation of 47%.

*Recap: This proposal outlines a new consensus rules change, it projects costs of $6,000 to produce the code and DCP, to be drawn from the core network development budget. The proposal is structured around two parts, one which gives a general overview of what the aim is, and another which gives a detailed technical account of how the changes will work. The aim of the change is to streamline the consensus change deployment process, so that future changes can be developed and rolled out more efficiently. While the proposed change streamlines the existing method of deploying stakeholder-approved hard forks, it will make it much more difficult to deploy any changes to consensus rules via a soft fork.*

**[Decred Content and Asset Translation Proposal (Phase 2)](https://proposals.decred.org/record/af9942a)**

Published Jun 15 by kozel | 6 comments (+5)

Final voting figures: 19,046 Yes votes, 527 No votes (97.3% Yes) - voter participation of 46%.

This proposal requests a budget of $33,000 for translation efforts over the remainder of 2021, eight months including work completed in May. The previous phase reported an underspend, using only $14,690 of the $33,000 budget. Decred Journal translations were the largest item, accounting for half of the budget, and a new release of Decrediton meant that software translations accounted for a larger than anticipated share of the spending on phase 1. @bee has stepped in to assist with management of the proposal, including by maintaining a translations [index](https://github.com/decredcommunity/translations/blob/master/index.md) (which also includes some translations not funded by the proposal).

## About this issue

Snapshot of Politeia data for this issue is based on this [commit]({link}).

Content for this edition was authored by @richardred with fixes from {name}.

Image credit: @30000fps

# Politeia Digest #66 - December 13 2023 - February 15 2024

![Image credit: @sænder](img/issue066/066-title.png)

**Treasury balance: 867,985 DCR (approx +6,864 DCR/month) - $15.2 million (+$120K/month) based on $17.48 DCR price**

## New Proposals

**[Cryptopower Phase 2: Golang Native Desktop & Mobile Wallet - Long Term Support](https://proposals.decred.org/record/eada888)**

Published Jan 29 by dreacot | last edited Feb 6 | 25 comments

This proposal requests a budget of $70,000 (but estimates it will use $34,500) for one year of maintenance and bug fixing for the Cryptopower multi-coin (DCR, BTC, LTC) wallet which was funded in a previous [proposal](https://proposals.decred.org/record/256efee). Of the previous proposal's budget of $61,600, 98% was spent, and progress was made with adding DCRDEX support (still beta), multi-recipient transactions, export options, UI improvements and a new instant exchange (Trocador), while the mobile apps (incorporating most desktop features but with some disabled due to usability constraints) were added to the Google and Apple stores.

The proposal will fund a year of improvements to the software and promises more frequent releases with patches every month addressing existing and new user feedback. The Gio framework will be updated to the latest version, DCRDEX will be made ready for mainnet use in the app, and the remaining time will be spent fixing bugs and making general improvements. For major additions to the app, specific proposals will be submitted requesting additional funding.

The proposal originally incorporated work on a number of new features, like virtual prepaid cards (budget $17,600), Trezor support (budget $8,800) and Ledger support (budget $8,800) - but was edited to remove these features and reduce the budget from $81,000, focusing on support of the software only, following community feedback.

Cryptopower is based in the Go language and uses [Gio](https://gioui.org/) to produce a graphical interface natively in Go for desktop and mobile/touch displays. During the last proposal some upstream issues were encountered with Gio and the Cryptopower team began sponsoring the Gio team with $500/month to facilitate resolving these issues, an arrangement which was expected to last for 4 months. This sponsorship will continue but only in months when the Cryptopower team needs some prioritisation of issue resolution.

The Apple Store raised concerns about the DEX and CEX exchange options of the app and whether these required KYC duties to be performed, as a result the exchange options were removed from the iOS version of the app to speed up approval, and a resolution will be sought which allows the exchange features to be added back in.

**[Decred Content and Asset Translations 2024](https://proposals.decred.org/record/a225e38)**

Published Feb 4 by kozel | 19 comments

This proposal requests a budget of $37,000 to fund a year of translation work, the last year's proposal had a budget of $33,000 and spent $18,955. The [translation index](https://github.com/decredcommunity/translations/blob/master/index.md) maintained by @bee lists articles which have been translated and most of those listed for 2023 will have been funded by the previous proposal, along with work that doesn't show up on a list like this, such as software product text translations, although the proposal states that this kind of work was relatively scant in 2023.

The most significant change for the new phase of this proposal is a change in policy towards translations which are contributed for languages that aren't well read by any established team or community members. There has been an issue with contributed translations sitting unreviewed for extended periods, preventing the translator from becoming a contractor billing for their work - so the decision was taken to relax the review requirements and settle for AI-assisted checking when it is not possible to obtain a review from a knowledgeable community member.

Comments on the proposal question the value of translating content like Decred Journal and Cypherpunk Times articles to languages like Polish, because potential readers of such technical material are likely to also be comfortable with English, and may prefer it for technical subjects. The other side of this is questioning the lack of translations for content like [docs.decred.org](https://docs.decred.org/), certain pages of the [decred.org](https://decred.org/) website and parts of the Decrediton user interface.

**[Decred Status platform](https://proposals.decred.org/record/2fc8466)**

Published Jan 29 by peter\_zen | last edited Feb 5 | 11 comments

This proposal requests a budget of $3,320 to build out a status page for Decred that will show whether certain Decred related services are online or offline, and be able to flag issues like DCRDEX going out of sync with the network. A proof of concept page has been created at https://is.decred.online/ using Uptime Kuma, a platform made for this purpose running on a VPS operated independently from Decred infrastructure. The status page monitors services like the Decred website, Matrix server, block explorer, proposals site, mixer servers, network seeders, and more - allowing users to determine whether issues they perceive are a result of a problem with the service or on the user's end.

The proposal would fund custom CSS to make the page follow Decred branding, configuration of probes that will allow for more detailed and useful reporting than the PoC site, and setting up notifications when outages are detected or certificates are about to expire. The deliverable is a GitHub repository with a Docker container that anyone can use to create their own instance of the status page, and the proposal also budgets $2,360 for running and maintaining an instance for a year. The work would be completed by @peter\_zen and @jholdstock.

Comments on the proposal are all very positive.

**[Decred Website Refresh 2024](https://proposals.decred.org/record/38a9726)**

Published Feb 4 by exitus | 7 comments

This proposal seeks approval from Decred Stakeholders to deploy a refresh of the [decred.org](https://decred.org/) website, and $3,250 compensation for the design and implementation work which has already been put into the refreshed website - which can be previewed at https://dcrweb.jholdstock.uk/ . The motivation for changes was to make the site more outreach friendly, more suited to people who may have seen an ad for Decred and have little other context coming in. Changes include new intro text and features section with graphics, key stats pulled from dcrdata, a new background image and quotes from Placeholder and Ark.

Comments on the proposal are positive about the refreshed website.

**[Decred Vanguard 2024](https://proposals.decred.org/record/d658f9a)**

Published Feb 4 by exitus | 10 comments

This proposal requests a budget of $78,640 for a second year of Decred Vanguard funding, reporting expenditure of $20,953 in phase 1 which was 45% of the requested budget of $46,784. Decred Vanguard is a way of rewarding and empowering community members who promote the project on social media. In the second year it will have 3 tiers of contributor with maximum monthly billing of $100 (7 slots), $400 (5 slots) or $1,500 (1 slot), for a total annual budget of $46,200 to pay contributors. The tier 3 member will be @exitus, who will also be responsible for running the new X Promoted Posts advertising campaign, a new addition to the Vanguard's effort that has a budget of $11,000. The program will also continue to pay for X premium for members (budget $1,320) to improve their effectiveness, as well as $120 for a Midjourney AI subscription. The proposal incorporates $20,000 discretionary funds, which will be used to fund giveaways (focusing more on Decred software this time, moving away from meme creation) and new unplanned initiatives. All of the budget figures are maximums, and it is anticipated that only around half of the budget will be used.

All of the comments are positive, some asking for more detail about what was learned during phase 1 and others offering suggestions for new modes of outreach and ways of tracking performance.

## Approved Proposals

**[Bug Bounty Program 2024](https://proposals.decred.org/record/a1fd5dd)**

Published Dec 8 by jholdstock | 6 comments (+3)

Final voting figures: 98% Yes Votes, 74% turnout of eligible tickets.

*Recap: This proposal requested a budget of $105,000, split between $100,000 for bounty payments and $5,000 for administrative costs. In the last 18 months covered by the previous [proposal](https://proposals.decred.org/record/da2f32d) there has been $415 paid out for bounties and operating costs of $1,750. The bug bounty program has been running for almost 5 years (since Jan 2019), and in that time 24 security vulnerabilities have been identified and fixed, and corresponding bounty payments worth $10,569 have been made to the people who found them. There is up to $30,000 available for vulnerabilities considered critical using the OWASP Risk Rating Methodology, so the requested budget is ample to keep the program going even if the rate and severity of bug reporting increases significantly.*

**[Decred Video Content 2024](https://proposals.decred.org/record/49cf2e1)**

Published Dec 8 by phoenixgreen | 13 comments (+11)

Final voting figures: 85% Yes Votes, 64% turnout of eligible tickets.

*Recap: This proposal requested a budget of $71,000 for the creation and dissemination of video content for 2024, it comes from the same team who have delivered the previous video content proposals. The requested budget is increasing to $5,920/month from $3,800/month, for 2023 the proposal billed a total of $39,847 ($3,321/month). Although the number of views and viewing time continued to grow steadily in 2023, growth in new subscribers is acknowledged as disappointing, with a net of just 27 new subscribers gained. The proposal considers a number of possibilities for improving the growth in subscribers: coordinating with Vanguard group to promote the content, Twitter livestreams, additional Twitter spaces, promoted ads for featured content on Twitter and Youtube, incentivising influencers to participate in livestreams and try Decred software. The proposal is open for new contributors, current team members are @phoenixgreen, @exitus, @karamble and @tivra - @exitus was the proposal owner previously.*

## About this issue

Content for this edition was authored by @richardred with review from @bee.

Image credit: @sænder

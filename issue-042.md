# Politeia Digest #42 - March 30 - May 1 2021

![Image credit: @30000fps](img/issue042/042-title.png)

**Treasury balance: 672,756 DCR (approx +11,066 DCR/month) - $141 million (+$2.3M/month) based on $209.09 DCR price**

## Proposals under discussion

**[Politeia: Pi (Proposal System) 2021 Q3](https://proposals.decred.org/record/91cfcc8)**

Published Apr 28 by lukebp | 2 comments

This proposal requests $118K to fund Backend ($64K) and Frontend ($54K) development of Politeia - it outlines a set of deliverables which are estimated to take around six months to complete, but it won't start until the [v1.1.0 release](https://github.com/decred/politeia/milestone/3) is completed. The proposal includes breakdown tables estimating the amount of time required in each of Design, Implementation and Verification phases. New features to be added in this batch include a DCR payments plugin that will allow customising the registration fee, making email optional, adding extra metadata to proposals and proposal author updates.

This was the first proposal to be published on the freshly deployed [Politeia v1.0.0](https://github.com/decred/politeia/releases/tag/v1.0.0), a major update to Politeia's architecture which adds a number of important features. A "tstore" backend has been added, based on a [Trillian](https://github.com/google/trillian) log (tlog) and a key-value store. One major advantage of this is scalability, which is significantly enhanced by the use of a database in place of Git. Separation of timestamps and data blobs also allows for specific items of content to be removed without wrecking the assurances for all of the other data. Other major changes concern the addition of a plugin architecture and a new API.

## Approved proposals

**[Design domain budgets: 03.21 - 12.21](https://proposals-archive.decred.org/proposals/76eba5a)**

Published Mar 25 by linnutee | 2 comments

Final voting figures: 11,208 Yes votes, 367 No votes (96.8% Yes) - voter participation of 28%

This proposal requested a maximum budget of $58,850 for Design team operations for the remainder of 2021. The proposal reports under-spending of ~60% against the previous Design proposal, mostly associated with the Identity (25% budget used) and Visual comms (38%) sub-domains. The proposal provided a [link](https://github.com/decred/dcrdesign/issues/252) to a full list of deliverables for the previous phase. The EETER design studio, a corporate contractor which has been leading Decred's Design effort, is winding down - but the staff who worked on Decred will continue to do so under the new company [t8d.xyz](https://t8d.xyz/).

A comment on the proposal from @checkmate expressed appreciation for the Design team's work and suggested that they may be able to help more broadly with the project's marketing effort. A reply from @linnutee indicated a preference for marketing proposals to bring their own design teams.

**[Video Content Production for Decred Phase 3](https://proposals-archive.decred.org/proposals/95a1409)**

Published Mar 27 by exitus | 6 comments

Final voting figures: 16,228 Yes votes, 346 No votes (97.9% Yes) - voter participation of 40%

This proposal requested a maximum budget of $19,200 for six months of video production - and reported billing for the previous six months of $6,720 (41% of previous budget). The team of eligible contractors working on the proposal is extended by two, with @karamble bringing a focus on video/gif animations and @Decred Society producing Decred Fundamentals videos. The proposal reports a small increase in views and engagement over phase 1, with 23,836 views for content in phase 2.

All of the comments on the proposal are supportive.

## Other news

Politeia was on a brief [hiatus](https://twitter.com/decredproject/status/1382793946993209344) in the run-up to the migration to v1.0.0 - this could not be deployed when proposals were making their way through the submission -> discussion -> voting flow.

## About this issue

Content for this edition was authored by @richardred with fixes from @bee.

Image credit: @30000fps

Previous issues of Politeia Digest have been corrected after mis-attributing the image credit, @30000fps should have been credited for the image used in issues 30, 31, 32, 33, 34, 36, 37, 39, 40, 41.

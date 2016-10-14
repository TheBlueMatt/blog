---
layout: post
title: Scaling Bitcoin Roundup
---

With Scaling Bitcoin over, and lots of interest in the conference, I figured I should post a summary of my views of how the conference went.

While this year's Scaling had a similar focus to the previous two, it seemed to have a different target audience. Instead of being focused making short- and medium-term scaling proposals accessible to a general audience for analysis, this this year's submissions and attendees seemed much more interested in sharing their work with the Bitcoin protocol development community and academics. This made for an incredibly exciting series of talks, with many new technologies to scale Bitcoin presented and discussed, as well as leading to a few misconceptions about the focus of those communities.

Though our CfP mentioned a few topics outside of scalability, the majority of both our submissions and presentations were primarily focused on it, with a number of talks having a refreshing focus on the tradeoffs and limitations (especially effects on fungibility) of various scalability solutions. Of the works presented, I wanted to call people's attention to a few of them to highlight the expanse of scaling solutions available to us in the (increasingly) near-term future, as well as to encourage the broader community to look closer at some technologies which might be important in discussing Bitcoin's path forward.

The TumbleBit submission was a particularly cool application of existing crypto primitives to create a novel scaling solution. The authors have managed to design a Chaumian-Ecash-like system, backed by Bitcoin, with hub-and-spoke payment channel-like scalability features, without almost any of the fungibility and privacy drawbacks inherent in such designs. (Note that their paper and the code they have released focuses primarily on the first-step mixing version, which requires more on-chain transactions per payment.) Thanks to works like this, I continue to be excited by the increasingly large range of second layer and exponential scaling solutions available, and am hoping they can find someone to help them implement the rest.

Greg Sanders' submission on SegWit takeaways and lessons learned provided useful considerations for those working on future protocol upgrades. Though the real effort was put in on Monday and Tuesday as one of the two remaining changes required for 0.13.1 was merged and the non-wallet parts of the other were heavily reviewed and finalized, the development challenges involved in implementing changes to Bitcoin is critical for us all to be aware of as we move forward.

The much longer-term continued research in reconsidering how we order transactions to form a "blockchain" is also exciting. The presentations on both braiding and combining PBFT-based signing with proof-of-work without negatively effecting Bitcoin's security will hopefully allow Bitcoin to support massively more on-chain transactions in the future.

In spite of the impressive number and types of scaling solutions presented, some attendees felt there was an important topic left out - namely hard fork design and rollout mechanics. Given the lack of thorough analysis of the topic and the seemingly constant discussion of it, it seems appropriate that it would be discussed at Scaling Bitcoin. This year, however, we received no submissions related to hard fork mechanics. Still, there were a number of private discussions around the issues involved, including several new hard fork rollout proposals. Hopefully this type of discussion can move more into the public eye as the protocol development community continues to explore the issues and design proposals, and as SegWit development nears completion.

Ultimately I found the conference to be an exciting venue for new proposals and look forward to the next one. Still, it seems likely we will continue to encourage a broader range of submissions, possibly with multiple tracks in future conferences.

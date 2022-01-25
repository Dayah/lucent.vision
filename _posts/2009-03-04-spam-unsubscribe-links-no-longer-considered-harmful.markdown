---
layout: post
title: Spam Unsubscribe Links Work
date: 2009-03-04 00:00:00 +0000
description: Thanks to the CAN-SPAM act, if you can read the message, the unsubscribe link probably works.
img: mail-slot.jpg
fig-caption: # Add figcaption (optional)
#tags: [Community Engagement]
---
Never follow the unsubscribe links in spam. Never even download the images in spam, or spammers will find out your address is real and give it to all their friends!

That’s what we’ve been taught, but spam filtering and the CAN-SPAM act have changed the game, and common knowledge no longer applies.

A decade ago, spam was freeform. Whatever style a spammer wished to use, they used. A spammer could express his own unique marketing personality through a combination of large text, colors, images, fonts, and grandiose language.

Then came server-side filtering and distributed rulesets, hashes, and lists of landing domains. Spam quickly became illegible nonsense. Bayesian filters could, in a way, statistically understand English sentences and flag them as spam. Hashes prevented spammers from sending the same message twice. Known landing sites showed us the nonsense domains spammers had to rent to get us to visit.

Spam filtering took into account both how the message was sent and what it contained. These two facets, in concert, allowed filters to become so good that for a message to make it through, it had to push the envelope of human readability.

The CAN-SPAM act then strongly bifurcated spammers. Some came into the light and followed the rules, using relevant subjects, no open relays, understandable language, and an unsubscribe link that supposedly functioned. Other went underground, doing their best to skirt the content filtering with nonsense text and day-old Chinese landing domains.

Each type sought to get through one of the two ways in which spam is filtered. Legally compliant spam used legitimate send methods to avoid detection by filters that looked at how a message was sent — while remaining legible and containing clear marketing language. Blackhat spam continued to use faster, dirtier methods of sending while disguising the content of the message that revealed it was marketing. Since each are attempting to bypass half of a complete filtering solution, a similar percentage of both currently gets through.

An especially interesting consequence of this bifurcation is that if you are reading a message with clear English sentences describing a product along with a relevant subject line, this message is highly likely to have a working unsubscribe link. Why? In order to reach you through modern server filters, the spam has to follow a lot of rules that blackhat spammers ignore because it would slow their spamming process to a crawl. The “legitimate” spam did not trigger filters that catch open relays or fake header information. Since the spammer took the time and effort to follow some of the rules that would end their business if reported under CAN-SPAM, it stands to reason they would also follow the working unsubscribe link rule.

I decided to test this hypothesis with one of the decade-old e-mail accounts on this domain, which received about 300 messages a day. On January 22, I began following every unsubscribe link in these messages. And I’m not talking about legitimate newsletters like NewEgg or MarketWatch, I’m talking about ShamWow and Acai Berry opt-outs. Within just a few days, the spam volume reduced to only 80 messages a day.

![Graph showing 300 messages a day declining to 75 a day](/assets/img/spam-decline.png)
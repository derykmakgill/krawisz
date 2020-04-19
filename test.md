---
layout: page
title: The Great Bitcoin Scaling Debate — An Annotated Timeline
---

This is a long, working document that is nowhere near complete. I attempt to show through a chronology of primary source material that Bitcoin was systematically hijacked and directed against its original vision of scaling on-chain.

#### 29 October 1995

In a discussion about Digicash on the Cypherpunk Mailing List, 
James A. Donald [critisizes](http://mailing-list-archive.cryptoanarchy.wiki/archive/1995/10/cedf031887bdce1f992b8382dc4c27486c61a68bebd117b9bf2818fa2d6dbe23/) 
the early electronic cash for having high fees.

>While Chaum is a brilliant cryptographer, he is an incompetent businessman
>
>He has demonstrated this in numerous ways.
>
>The latest being "Cash" where the bank skims off 4% to 10% every time.
>
>No one is going to use digicash under these kinds of terms and 
conditions.

#### 30 Oct 1995

Creator of the Cypherpunk Mailing List Timothy C. May [responds](http://mailing-list-archive.cryptoanarchy.wiki/archive/1995/10/cedf031887bdce1f992b8382dc4c27486c61a68bebd117b9bf2818fa2d6dbe23/) 
in agreement.

>I don't know if the "skims off 4% to 10% every time" point accurately
describes how the current Digicash model works, but certainly this will not
fly as a long term rate. So many monetary transactions happen in the course
of business that even a 4% fee _per transaction_ would rapidly wipe out
most of the value.

#### 14 June 1996

Hal Finney argues for the [utility of online micropayments](http://mailing-list-archive.cryptoanarchy.wiki/archive/1996/06/b2345507ef1258011af9ea463ae9b03714f5cd29c4092458bd0002b360f1d545/) on the Cypherpunk Mailing List.

>Consider two sites, one which acts as a proxy and cache but which
charges something under a penny per page, and another which acts for
free.  Won't the for-pay site be able to afford a larger disk, more
servers, and better net connections?  It will be a superior service.
>
>Micropayments will allow new services and improved quality over what we
have today where we have to rely on charity and advertising as
motivations for much of what we find on the web.

#### 02 May 1997

Blockstream founder and Hashcash inventor Adam Back [writes](http://mailing-list-archive.cryptoanarchy.wiki/archive/1997/05/ef17e389556d2b6e27e8e0036a85ce1fedc73e2de871cc30728e7fc8be3d7f09/) 
on the Cypherpunk Mailing List that a successful digital cash project must be ultra low cost to transact with.

>What we want is fully anonymous, *ultra low transaction cost,* transferable units of exchange.  If we get that going the banks will become the obsolete dinasaurs they deserve to become.

#### May 1999

Nick Szabo publishes [*Micropayments and Mental Transaction Costs.*](https://nakamotoinstitute.org/static/docs/micropayments-and-mental-transaction-costs.pdf) The paper argues against the viability of online micropayments and suggests security is a more important investment than reducing network resource usage to enable cheaper transactions.

>A lesson for micropayment efforts is that mental costs usually exceed, and
often dwarf, the computational costs. Reductions in the per transaction computational costs of transactions may often be economically insignificant. Other transaction costs addressable by hardware or software, such as security concerns,
as well as costs of better communicating product quality versus price tradeoffs
in the user interface, are usually more important ob jectives for technological
cost reduction than conserving on computational or network resources.

#### 14 July 2010

A <code>max_block_size</code> [value of 1MB](https://github.com/bitcoin/bitcoin/commit/a30b56ebe76ffff9f9cc8a6667186179413c6349#diff-118fcbaaba162ba17933c7893247df3aR2614) set on the client.

#### 22 July 2010

The Bitcoin.org website on [Wayback Archive](https://web.archive.org/web/20100722094110/http://www.bitcoin.org:80/) lists the main advantages of Bitcoin on the homepage. In bold, it says:

> Bitcoin transactions are practically free, whereas credit cards and online payment systems typically cost 1-5% per transaction plus various other merchant fees up to hundreds of dollars.

#### 19 September 2010

After some discussion, Hal Finney, Satoshi (Bitcoin’s creator), and the user ‘Cryddit,’ who is Ray Dallingerr, on Bitcointalk imposed a [1MB default block size](https://github.com/bitcoin/bitcoin/commit/172f006020965ae8763a0610845c051ed1e3b522) to reduce the chance of spam transactions hijacking blockspace, or the possibility of cheap DoS attacks. [Cryddit below explains why this limit was put in place:](https://bitcointalk.org/index.php?topic=946236.msg10388435#msg10388435)

>I'm the guy who went over the blockchain stuff in Satoshi's first cut of the bitcoin code.  Satoshi didn't have a 1MB limit in it. The limit was originally Hal Finney's idea.  Both Satoshi and I objected that it wouldn't scale at 1MB.  Hal was concerned about a potential DoS attack though, and after discussion, Satoshi agreed.  The 1MB limit was there by the time Bitcoin launched.  But all 3 of us agreed that 1MB had to be temporary because it would never scale.
>
>Several attempted "abuses" of the blockchain under the 1MB limit have proved Hal right about needing the limit at least for launching purposes.  A lot of people wanted to piggyback extraneous information onto the blockchain, and before miners (and the community generally) realized that blockchain space was a valuable resource they would have allowed it.  The blockchain would probably be several times as big a download now if that limit hadn't been in place, because it would have a lot of random 1-satoshi transactions that exist only to encode information for altcoins etc.
>
>At this point I don't think random schmoes who would allow just any transaction are getting a  lot of blocks. The people who have made a major investment in hashing power are doing the math to figure out which tx are worthwhile to include because block propagation time (and therefore the risk of orphan blocks) is proportional to block size. So at this point I think blockchain bloat as such is no longer likely to a problem, and the 1MB limit is no longer necessary.  It has been more-or-less replaced by a profitability limit that motivates people to not waste blockchain bandwidth, and miners are now reliably dropping transactions that don't pay fees. 

#### 01 December 2010

One of the [earliest posts](https://www.reddit.com/r/Bitcoin/comments/eef3h/a_short_introduction_to_bitcoin_a_peer_to_peer/) on r/Bitcoin is made linking to an article titlted *A Short Introduction to Bitcoin - A Peer to Peer Cryptocurrency.* The [linked article](https://bluishcoder.co.nz/2010/10/10/a-short-introduction-to-bitcoin.html) describes the author's interest in Bitcoin's ability to offer micropayments.

>I'm interested in the approach of using bitcoin as a way to do micro-transactions and ease online payments and donations.

#### 19 July 2011

r/bitcoin moderator u/AtlasLGo is [accused](https://bitcointalk.org/index.php?topic=30211.0) of trying to sell r/bitcoin. In the ensuing drama, someone contacts Reddit and he is removed along with three other mods we can see on the [WayBack Machine](https://web.archive.org/web/20110530125818/https://www.reddit.com/r/Bitcoin/new/) as late as May 2011.

Theymos becomes the new sole [moderator](https://bitcointalk.org/index.php?topic=30211.msg381922#msg381922) and refuses to allow the old ones back in. We see him as the sole moderator on the WayBack machine in [September 2011.](https://web.archive.org/web/20110927021847/https://www.reddit.com/r/Bitcoin/new/)

Now former moderator u/edzillion [recounted](https://www.reddit.com/r/btc/comments/84djb8/did_theymos_purchase_rbitcoin_in_2011/dvqcdvp?utm_source=share&utm_medium=web2x) the story years later: 

>Atlas was basically inactive - it seemed the modding was going just fine (it was a very positive community in those early days) but then one day without any warning we were all kicked. It seems atlas was chatting with people over IRC and they were like how can you sell it? and he booted all the other mods in preparation for a sale.
>
>This caused a total shitstorm, as you can imagine, and the community basically shouted loud enough that the orig mod backed down and agreed to hand it over to whoever the community decided, which was theymos.
>
>Theymos wasn't much better - wouldn't re-add any of the kicked mods and held it alone himself on some kind of power trip. Things got quite unfriendly after that - partially because theymos is a typical angry asshole libertarian, and partially because the scene grew so much that it was hard to maintain a close community.
>
>After a while of lobbying to get back in and failing, I gave up on it but I still feel disabused by that situation. I put a lot of good work into making bitcoin and r/bitcoin what it is today. We were all crazy wide-eyed zealots back then shouting it from the rooftops. I figured I at least deserved some kind of explanation, let alone my modship (which, let's face it is a somewhat useful position in the btc world).

#### 12 June 2015

Chinese miners signed a statement that they want [8MB blocks.](https://www.reddit.com/r/Bitcoin/comments/3a0n4m/why_upgrade_to_8mb_but_not_20mb/?utm_source=share&utm_medium=web2x) Signatories included the large mining companies F2pool, BTCChina, Antpool, Huobi, and BW.

![Miners Want Big Blocks](https://miro.medium.com/max/1400/0*3fpU-5KaDHJjXFao.)

In an article translated on Medium, the miners argue:

>If the current network is incapable of supporting blocks larger than 1MB, then Core’s insistence on the block size limit is understandable. But actually, even with the Great Firewall in place, Chinese mining pools have all said they want an 8MB block size.

#### 13 August 2015

/u/aminok has his post [(archive)](https://archive.is/E75Cx#selection-1969.95-1969.299) deleted, in which he asked the mods: “please don’t try to impose your will on the Bitcoin community.” 

>Allow posts that promote hard forks in the sub. A hard fork to raise the hard limit has been part of the development plan for Bitcoin since 2010. Posts about it are entirely appropriate for this subreddit.

He posted a [private message](https://www.reddit.com/r/bitcoin_uncensored/comments/3gxup6/another_meta_post_deleted_in_rbitcoin_what_can_we/cu2j0ea?utm_source=share&utm_medium=web2x) he received from the moderrators about it in an uncensored Bitcoin subreddit.

>Regarding the specific post that was removed: There have been several front-page posts about r/Bitcoin's XT-related moderation over the last few days. Your post added nothing to this discussion and was generally repetitive. See the rules:
>
>Please avoid repetition — r/bitcoin is a subreddit devoted to new information and discussion about Bitcoin and its ecosystem.
>
>Even if you think that something is important, you can't keep bringing it up day after day on r/Bitcoin without some significant+notable additional thoughts/news. It might get upvoted, but overall it's annoying and hurts the usability of r/Bitcoin.

#### 16 August 2016

A popular Bitcoin webcomic artist /u/raisethelimit was given a [30 day ban](https://www.reddit.com/r/bitcoin_uncensored/comments/3h8tf2/uraisethelimit_was_banned_for_30_days_for_posting/) for “trolling” when he tried posting two of his comics there. Some of the comics he made over the years are archived below.

![The Hypocrisy of a Thermos](https://i.imgur.com/2uDkC6g.jpg?1)

![There Is No Fork](https://i.imgur.com/ICFiTVO.jpg?1)

A now-deleted user responds in the thread [confirming he was banned](https://www.reddit.com/r/bitcoin_uncensored/comments/3h8tf2/uraisethelimit_was_banned_for_30_days_for_posting/cu5a6so?utm_source=share&utm_medium=web2x) on the same day for posting that raising the block size does not make Bitcoin an 'altcoin.'

>I was just banned as well for... linking to a post that explained why bitcoin XT was not an altcoin (I'm assuming... there was no reason given yet).
>
>To me it's clear that they are seeing the stats on xtnodes.com and are shitting their pants. Five days ago thermos said "the actual chance of XT defeating Bitcoin is nearly zero." https://www.reddit.com/r/Bitcoin/comments/3gjrvy/could_we_have_a_sticky_on_the_new_rules_their/ctzoeyt
>
>Now, I understand this graph is just getting started, but it doesn't look good for them 24 hours in:
>
>http://www.xtnodes.com

#### 07 September 2015

r/bitcoin moderator u/hardleft121 announces he was removed by Theymos as moderator over a week ago and 'thanked' for his services.

The response was largely outrage, the most [popular reply](https://www.reddit.com/r/Bitcoin/comments/3k0iji/i_am_no_longer_a_mod_of_rbitcoin_i_didnt_have/cuturbe?utm_source=share&utm_medium=web2x) suggesting Theymos appoint Hitler, Stalin and Mao as moderators. A now deleted user [wrote:](https://www.reddit.com/r/Bitcoin/comments/3k0iji/i_am_no_longer_a_mod_of_rbitcoin_i_didnt_have/cutuscp?utm_source=share&utm_medium=web2x)

>I believe that's because Theymos is hand-selecting mods only who follow in his exact instructions and censorship. They have to be devoted minions or they will be removed.

Indeed only a week after his removal, u/hardleft121 wrote that ['Gavin and Mike are right'](https://www.reddit.com/r/Bitcoin/comments/3jgtjl/i_support_bip101/cuqdm54/?context=3) in [BIP 101,](https://github.com/bitcoin/bips/blob/master/bip-0101.mediawiki) a proposal to raise the Bitcoin block size. 

#### 28 December 2015. 

A rogue /r/bitcoin mod going by the username /u/CensorshipIsTheWorst leaked the following conversation from the /r/Bitcoin mod-mail:

>from Aussiehash [M] to /r/Bitcoin sent 1 day ago https://np.reddit.com/r/Bitcoin/comments/3ycayp/brian_armstrong_on_twitter_coinbase_is_now/ I’ve removed this post for now. I’m happy for other mods to reverse or otherwise.
>
>from theymos [M] via /r/Bitcoin to Aussiehash [M] sent 11 hours ago I agree with removing it because it is mainly about XT. However, AFAICT Coinbase is currently still using Bitcoin and should therefore be allowed on /r/Bitcoinfor now in general. coblee said so in the bitcoin.org pull request, and I tend to trust him. (Perhaps Cobra was unaware of coblee’s reliability, or maybe he [IMO reasonably] considered Coinbase too dangerous/incompetent/reckless to list on bitcoin.org even though they are currently using Bitcoin.)

>from StarMaged [M] via /r/Bitcoin to theymos [M] sent 5 hours ago Honestly, it seems to me that until the moment of the split, they are still a bitcoin company. They are just buying/selling two currencies at once instead of one. I am really uncomfortable with the idea that this policy would encourage companies to silently support XT and then only tell us at the last moment. Yeah, sure, remove those posts as altcoin promotion, but people outside of this subreddit should be allowed to make an informed decision without us scaring companies into censoring themselves. I feel that this is where that term “censorship” might actually be relevant, since our actions here on this issue would affect the speech of a company elsewhere out of fear of retaliation from this subreddit. Something to ponder.

A few hours later, /u/colsatre had his moderator position revoked, leading some to speculate that he was the rogue mod. /u/CensorshipIsTheWorst never posted again.

/u/colsatre wrote later under his own account critisizing Theymos for censorship and said he was removed for not following the [party line.](https://www.reddit.com/r/btc/comments/40rqrd/ustarmageds_last_action_as_a_mod_was_great_but/cywu8nz?utm_source=share&utm_medium=web2x)

>I didn't leave of my own volition either. Other mods, specifically theymos, weren't happy with actions I took.

>I'm not a fan of sticking around a place where dissenting opinions are liable to be removed...

>I'm one of the regulars from back then that /u/Shadered mentioned, I was a mod here on r/Bitcoin and bitcointalk for a while. Those places are no longer for me!

>He's either extremely incompetent or malicious with the way he went about it. There was no discussion with the rest of the forum staff before giving money to Slickage.
>
>I find it hard to believe that he'd be that stupid. He also refused to answer any questions about it afterwards, which leads me to believe he did something that he knew was shady.
>
>Source - Was a mod of bitcointalk at the time it happened

On an article documenting some of the censorship on r/Bitcoin over the years, he [commented:](https://www.reddit.com/r/btc/comments/5cue13/john_blocke_a_brief_and_incomplete_history_of/d9zzmkq?utm_source=share&utm_medium=web2x)

>Seems to be a very good and accurate write-up!

He also supported [raising the Bitcoin block size to 2mb.](https://www.reddit.com/r/Bitcoin/comments/5q1v0q/are_your_transactions_slow_to_confirm_then_ask/dcvseif?utm_source=share&utm_medium=web2x)

>Can't we just bump the block size to 2mb?

#### 08 January 2016

A thread in r/Bitcoin titled *Scalability issue is a red-herring* argues Bitcoin is a store of value first and by implication suggests we don't need to raise the block size. The thread has 51 comments and zero upvotes.

Theymos comments in agreement and is heavily downvoted.

>If that requires treating bitcoins like Yap stones, that's still better than what we had before Bitcoin.

u/Uber_Nick responds, questioning Theymos on deleting comments he disagrees with.

>Does "better and freer" mean users won't be banned from discussing ideas that are different than yours?

Theymos replies and is heavily downvoted.

>No one is ever banned for discussing ideas that are different than mine. Banning someone for that reason would be completely at odds with my philosophy of moderation.

Seems rational? But when we use the [Removeddit tool,](http://removeddit.com/r/Bitcoin/comments/404z6b/scalability_issue_is_a_redherring/) we can see 24% of the comments on the entire are removed, most of which appear to have been in response to Theymos' defense of his moderation policies.

#### 26 January 2016

Greg Maxwell posts defending the [censorship in r/Bitcoin.](https://www.reddit.com/r/Bitcoin/comments/42u1v8/core_devs_communication_has_improved_thank_you/czdesxq/)

> r/btc at this moment is smoking hot proof that r/bitcoin is doing something right and that it's not just a question of moderator punishment.

#### 11 September 2017

Bitcoin Core developer Matt Corallo submits a [filing](https://www.sec.gov/comments/sr-nysearca-2017-06/nysearca201706-161046.htm) to the Securities and Exchange Commission to ask them to step in and protect consumers from attempts to create a new Bitcoin.

>I am Matt Corallo, a long-time developer of Bitcoin (around the 10th publicly recorded individual to contribute to the Bitcoin codebase), an expert on Bitcoin's operation, vocal Bitcoin advocate, and strong proponent of the availability of a Bitcoin Exchange-Traded Product (ETP).
>
>I have very grave concerns with the proposed rules for the maintaining of Bitcoin deposits and the lack of consumer protection in the event of Bitcoin Network rule changes in the current filings.
>
>As described in the S-1 filing for the "Bitcoin Investment Trust" (BIT), a "permanent fork" of Bitcoin may occur when two groups of users disagree as to the rules which define the system (its "consensus rules"). More specifically, such a "permanent fork" is likely to occur when one group of users wish to make a change to Bitcoin's consensus rules, while another group does not. This leads to two cryptocurrencies, and may lead to significant ambiguity around which should be referred to as "Bitcoin".



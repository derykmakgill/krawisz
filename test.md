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

#### 07 September 2015

r/bitcoin moderator u/hardleft121 announces he was removed by Theymos as moderator over a week ago and 'thanked' for his services.

The response was largely outrage, the most [popular reply](https://www.reddit.com/r/Bitcoin/comments/3k0iji/i_am_no_longer_a_mod_of_rbitcoin_i_didnt_have/cuturbe?utm_source=share&utm_medium=web2x) suggesting Theymos appoint Hitler, Stalin and Mao as moderators. A now deleted user [wrote:](https://www.reddit.com/r/Bitcoin/comments/3k0iji/i_am_no_longer_a_mod_of_rbitcoin_i_didnt_have/cutuscp?utm_source=share&utm_medium=web2x)

>I believe that's because Theymos is hand-selecting mods only who follow in his exact instructions and censorship. They have to be devoted minions or they will be removed.

Indeed only a week after his removal, u/hardleft121 wrote that ['Gavin and Mike are right'](https://www.reddit.com/r/Bitcoin/comments/3jgtjl/i_support_bip101/cuqdm54/?context=3) in [BIP 101,](https://github.com/bitcoin/bips/blob/master/bip-0101.mediawiki) a proposal to raise the Bitcoin block size. 

#### 11 September 2017

Bitcoin Core developer Matt Corallo submits a [filing](https://www.sec.gov/comments/sr-nysearca-2017-06/nysearca201706-161046.htm) to the Securities and Exchange Commission to ask them to step in and protect consumers from attempts to create a new Bitcoin.

>I am Matt Corallo, a long-time developer of Bitcoin (around the 10th publicly recorded individual to contribute to the Bitcoin codebase), an expert on Bitcoin's operation, vocal Bitcoin advocate, and strong proponent of the availability of a Bitcoin Exchange-Traded Product (ETP).
>
>I have very grave concerns with the proposed rules for the maintaining of Bitcoin deposits and the lack of consumer protection in the event of Bitcoin Network rule changes in the current filings.
>
>As described in the S-1 filing for the "Bitcoin Investment Trust" (BIT), a "permanent fork" of Bitcoin may occur when two groups of users disagree as to the rules which define the system (its "consensus rules"). More specifically, such a "permanent fork" is likely to occur when one group of users wish to make a change to Bitcoin's consensus rules, while another group does not. This leads to two cryptocurrencies, and may lead to significant ambiguity around which should be referred to as "Bitcoin".



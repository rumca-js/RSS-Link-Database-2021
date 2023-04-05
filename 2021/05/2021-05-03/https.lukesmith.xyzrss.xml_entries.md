# Source:Luke Smith, URL:https://lukesmith.xyz/rss.xml, language:en-US

## Monero and Other Privacy Coins
 - [https://lukesmith.xyz/articles/monero-and-other-privacy-coins/](https://lukesmith.xyz/articles/monero-and-other-privacy-coins/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2021-05-04 00:00:00+00:00

<p>As I said <a href="https://lukesmith.xyz/posts/monero-maximalism-or-how-bitcoin-is-a-coin">in other writings</a> and
<a href="https://videos.lukesmith.xyz/videos/watch/8ba38c94-e8c2-421f-bb5f-47f4169fa804">videos</a>,
no serious cryptocurrency can function <strong>in real life</strong> which is not
also a <em>truly private</em> cryptocurrency.</p>
<p>By far, the most popular of all these is Monero, which has already
become the <em>de facto</em> currency of the dark web, but also of <em>all</em>
cryptocurrency users <em>who actually use cryptocurrency for purposes other
than a mere investment</em>.</p>
<p>Monero, however, is not actually the only private or pseudo-private
crypto-currency, and while I talked about its competitors in a recent
stream, I think it's worth putting in words for a reference.</p>
<h2 id="moneros-competitors">Monero's Competitors</h2>
<h3 id="zcash-is-trash">Zcash is Trash</h3>

<figure class="resright"><a href="https://lukesmith.xyz/pix/zcashy_owned.png"><img src="https://lukesmith.xyz/pix/zcashy_owned_small.png" /></a></figure>

<p><strong>Optional privacy is no privacy at all.</strong></p>
<p>Zcash (ZEC) is often shilled as a Monero replacement. On the surface it
actually sounds great and unambiguously better: it has a clever a
zero-knowledge proof technology called zk-SNARKs which can store and
prove transactions in the blockchain in a private way. zk-SNARKs are
generally superior to Monero's somewhat ragtag triad of ring
signatures + stealth addresses + ring CT to anonymize transactions and
they are more scalable.</p>
<p>zk-SNARK is short for &quot;Zero Knowledge Succinct Non-interactive ARgument
of Knowledge.&quot;</p>
<ul>
<li>Zero Knowledge &ndash; It is private.</li>
<li>Succinct &ndash; Referring to computation time.</li>
<li>Non-interactive &ndash; In some earlier implementations of the
technology, the interacting parties must exchange information and
negotiate in turns, while zk-SNARKs can occur instantaneously.</li>
</ul>
<p>Zcash, however, has two major problems, one substantial and one
accidental (in the Aristotelean sense).</p>
<p>The substantial problem is that zk-SNARKs <em>are not fully trustless</em>:
they require a trusted setup where public parameters are generated and
if not properly disposed of, the initial developers could use that
knowledge to produce infinite money without anyone knowing. This sort of
defeats the purpose of having a decentralized cryptocurrency and while
the rest of the currency is decentralized, that gaping hole certainly
isn't.</p>
<p>The accidental problem (or maybe <em>incidental</em> problem in modern English)
is that Zcash is only <em>optionally private</em>. The vast majority of ZEC
transactions are not &quot;shielded&quot; with the zk-SNARK technology, but are
as public as a Bitcoin transaction. <strong>This allows a third-party to
uncover the &quot;private&quot; transactions by a process of automatic process
of elimination.</strong></p>
<p>Zcash, while is created valuable technology, is simply not a private
currency and is not a valid competitor to Monero.</p>
<h3 id="pirate-chain">Pirate Chain</h3>
<p>Pirate Chain (ARRR) is a minor privacy coin that has mooned
significantly recently popping up from 30 cents to 14 dollars or so
(it's halved since I started writing this article though). Pirate Chain
uses the zk-SNARK technology, but unlike Zcash, uses it mandatorily
(with optional transparent transactions like Monero via the private view
key).</p>
<p>Pirate Chain has two big issues though. The first is what I mentioned
before: zk-SNARKs as they have been implemented in ZEC and ARRR are
<strong>not trustless</strong>. They require a setup in which theoretically, if the
public parameters of the system were known to some inside party, they
could print an infinite amount of the currency with absolutely no way
that any other people could know.</p>
<p>Even if you <em>trust</em> the Pirate Chain developers, Pirate has another
pretty undeniable problem: <strong>90% of ARRR has already been mined and is
in circulation!</strong> Yep, you heard that right: A minor niche alt-coin
which has existed for only three years was put together in such away
that now as big of a proportion of it has been mined as has been mined
of Bitcoin in over ten years!</p>
<p>That means that that 90% is highly aggregated in the wallets of the two
and a half people who knew of ARRR in this period, and anyone adding to
the market cap is mostly just contributing to these people's bags. Even
if Pirate Chain had great trustless technology (which is doesn't) it
has not been set up equitably, but in a way that enriches early adopters
to an extreme degree. Expect to get dumped on if you buy this stuff.</p>
<p>Honestly, if you want a better, more honest cryptocurrency, you could
just take the Pirate setup and give it a slower and more sane emission.
That would be a better choice than ARRR itself.</p>
<h3 id="monero--dogecoin--bitcoin--wownero">Monero + Dogecoin + Bitcoin = Wownero</h3>

<figure class="resright"><img src="https://lukesmith.xyz/pix/nowow.jpg" /></figure>

<p><a href="https://wownero.org">website</a> &ndash; <a href="https://suchwow.xyz">meme site</a></p>
<p>Wownero is a joke currency. It's literally a fork of Monero with
Dogecoin aesthetics and some minor additions. Like Pirate Chain, it also
has surged significantly recently (from 2 or 3 cents to more than a
dollar&mdash;beating out Dogecoin as a pump-and-dump for sure).</p>
<p>Weirdly enough, Wownero is probably the best of the alternative privacy
coins that I've mentioned so far. It's trustless, unlike the zk-SNARK
coins, but also has some nice features.</p>
<p>It was created somewhat as a satirical response for another privacy
💩coin, MoneroV, which was just Monero with an initial coin offering and
forked from the same blockchain (which ruins the privacy of users on
both chains because it becomes easier to triangulate on when outputs are
actually spent).</p>
<p>Since Wownero is a &quot;joke,&quot; it actually has integrated new technology
and helpful additions <em>before</em> Monero has, since the Wownero developers
are doing it all fast and loose. Ironically, that can be good.</p>
<p>One principle division between Monero and Wownero is that Wownero is
more like Bitcoin in that it has a totally fixed supply, while Monero
has tail emission. Some people have criticized Monero for tail emission,
arguing that it is unnecessary and inflationary. I am not sold on either
side: the game theoretics of this has never truly played out, but
Wownero might actually be something to look into if you like Monero, but
think it's &quot;inflationary.&quot; Regardless, Wownero's whitepaper and
roadmap on their website are something that everyone should read and
take seriously.</p>
<p>Again, the currency is sort of a meme, but it is what it is. I decided
to start taking <a href="https://lukesmith.xyz/crypto.html">Wownero donations</a> on my site a while
ago, just for fun.</p>
<h3 id="suterusu-and-the-suter-token">Suterusu and the Suter Token</h3>
<p><a href="https://suterusu.io/">website</a></p>
<p>Now the ideal private currency would have the simple and scalable
zk-SNARK technology implemented in a fair way and hopefully started in
some novel manner that is truly trustless. Suterusu is one potential
candidate for this kind of system. Behind it is a novel idea of
zk-conSNARKs which can be read about in their
<a href="https://github.com/suterusu-team/suterusu-documents/raw/master/Suterusu_whitepaper.pdf">whitepaper</a>,
their
<a href="https://github.com/suterusu-team/suterusu-documents/raw/master/Suterusu_yellowpaper%20V%200.2.pdf">yellowpaper</a>
and a document on <a href="https://github.com/suterusu-team/suterusu-documents/raw/master/Suterusu_architecture.pdf">Suterusu
architecture</a></p>
<p>This technology hasn't been extensively vetted, but it has the
potential to solve all the issues in privacy coins.</p>
<p>Suterusu isn't quite meant to be an analog of Monero. The token itself
is actually just an Ethereum token. In fact, this might be the
interesting part: Part of its system is that it can provide zk-conSNARK
shielding <em>to other currencies</em> that support smart contracts. You can
use Suter to transact with Ethereum privately, for example.</p>
<p>The Suterusu system, however is not perfect as far as I'm concerned. It
isn't a self-propelling decentralized system in the way that Bitcoin or
Monero is. That makes is regulatable and subject to human whim in a way
a cryptocurrency should not be. It is a designed system with dev taxes
and even <a href="https://medium.com/suterusu/regulation-compliance-of-suterusu-625abc752eb9">regulatory compliance that includes
blacklisting</a>.</p>
<h2 id="zk-snarks-vs-zk-starks">zk-SNARKs vs. zk-STARKs</h2>
<p>In addition to the zk-S<strong>N</strong>ARK system used in Zcash and Pirate, there
also exists zk-S<strong>T</strong>ARKs, which like zk-conSNARKs allow for a trustless
setup. <a href="https://eprint.iacr.org/2018/046.pdf">Whitepaper</a>.</p>
<p>To repeat, zk-SNARK stands for &quot;Zero Knowledge Succinct Non-interactive
ARguments of Knowledge.&quot; zk-S<strong>T</strong>ARK stands for &quot;Zero Knowledge
<strong>Scalable Transparent</strong> ARguments of Knowledge.&quot; [Scalable]{.dfn}
because it scales better than zk-SNARKs and [transparent]{.dfn} because
it has a trustless setup.</p>
<p>I do not know of a currency project that uses this technology now. Like
zk-conSNARKs, it's only a couple years old.</p>
<h2 id="the-ideal-privacy-coin">The ideal privacy coin</h2>
<p>Would be one that:</p>
<ol>
<li>Is actually private.</li>
<li>Is trustless.</li>
<li>Is highly scalable.</li>
<li>Is truly decentralized and unmanaged by a singular entity.</li>
<li>Has reasonably fair emission/mining schedule.</li>
</ol>
<p>Monero gets only half credit on 3, but full points on the rest. Wownero
is the same, although perhaps it should be taken less seriously as a
Doge-tier joke. Zcash fails on 1 and 2. Pirate Chain fails on 2 and 5.
Suterusu has great tech, but flounders on 4.</p>
<p>So the recipe for an ideal currency is here. It is one that implements
the zk-conSNARK technology of Suterusu or zk-STARKs (provided that such
technology is appropriately vetted), but does so in a way without
centralization, dev taxes and other self-refuting silliness.</p>
<p><strong>This ideal currency might just be Monero itself</strong>, to my understanding
Monero has contemplated integrating zk-STARKs as they become more
well-travelled. Such an addition, if it works, would drastically improve
the scalability of Monero even if it might require somewhat of an
overhaul.</p>
<hr />
<h2 id="donate">Donate</h2>
<ul>
<li><img alt="" src="https://lukesmith.xyz/pix/xmr.svg" /> Monero &ndash; <code>48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code></li>
<li><img alt="" src="https://lukesmith.xyz/pix/wow.svg" /> Wownero &ndash; <code>Wo3kx9FY1sQLndodemcibifzbdi2Q7X9YaoaMAVdKCwXieVJBJTRdpG3WoWzQ1atnBLK1Wti7P72p34K21EaACRv124yiLenE</code></li>
</ul>


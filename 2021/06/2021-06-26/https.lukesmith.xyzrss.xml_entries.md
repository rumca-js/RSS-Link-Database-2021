# Source:Luke Smith, URL:https://lukesmith.xyz/rss.xml, language:en-US

## Matrix vs. XMPP
 - [https://lukesmith.xyz/articles/matrix-vs-xmpp/](https://lukesmith.xyz/articles/matrix-vs-xmpp/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2021-06-26 00:00:00+00:00

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/xmpp.svg" title="The Chad XMPP" /></figure>

<h2 id="what-are-xmpp-and-matrix-and-what-makes-them-special">What are XMPP and Matrix and what makes them special?</h2>
<p>XMPP and Matrix are two decentralized and federated free sofware
projects for chat, including true end-to-end encrypted chat.</p>
<p>Users can either install the software on their own server if they want,
but they can also easily register on any public server&mdash;both allow any
XMPP or Matrix user to talk to users on their server or on any other
one. In essence, it works like email: you might have an email account on
a different site than your friend, but all accounts on all sites can
communicate.</p>
<p>In a world where most communication is done on centralized proprietary
platforms without end-to-end encryption like Facebook, Telegram and
Google, Matrix and XMPP both are permanent solutions to communication
privacy. Even based boomerware like IRC has to play second fiddle to
them.</p>
<p>The only question is, &quot;Which is better? XMPP or Matrix?&quot;</p>
<h2 id="matrix-vs-xmpp-which-is-better">Matrix vs. XMPP: Which is better?</h2>
<p>After timely research and experience, I will say that XMPP is superior
to Matrix. I'll talk about why here, but I'll firstly discuss
Matrix's apparent advantages over XMPP.</p>
<p>There are some use-cases where Matrix is preferrable to use and Matrix
is somewhat easier for normal people to start using. However, Matrix,
although it is still end-to-end encrypted has larger metadata
liabilities. Although Matrix is decentralized, there are many issues
that make it too reliant on the &quot;main&quot; Matrix.org server. It also has
more significant problems in that metadata is spread from server to
server.</p>
<h3 id="matrixs-advantages-over-xmpp">Matrix's advantages over XMPP</h3>
<h4 id="matrix-is-more-normie-friendly">Matrix is more normie friendly.</h4>
<p>Although there are <a href="https://matrix.org/clients/">many Matrix clients out
there</a>, there is one &quot;primary&quot; one,
Element (formerly called Riot). Element is a lot more streamlined and
easier to use than most all other clients, and it is available on all
platforms. This is because it is an odious Electron-based application,
but that it is a big advantage to be able to tell your friends just
about one program they can use on all platforms.</p>
<h4 id="matrix-now-comes-end-to-end-encrypted-by-default">Matrix now comes End-to-end encrypted by default.</h4>
<p>The standard Matrix-Synapse server now encrypts all chats and private
rooms with end-to-end encryption by default. This is not the case for
most XMPP servers. For example, OMEMO encryption can be used with XMPP
servers, but it usually requires extra setting up and many XMPP clients
do not have proper or easy compatibility with default End-to-end
encryption (you may have to manually select to encrypt communications
for each chat).</p>
<h4 id="matrixs-default-functionality-is-more-intuitive">Matrix's default functionality is more &quot;intuitive.&quot;</h4>
<p>If someone sends you a message, you expect it to show up on all your
devices, not just the one that checks first. When you install a new
application on your phone, you sort of expect it to be able to view
previous conversations in the chat. XMPP does not necessarily work like
this by default (I should say that some XMPP servers do allow this), but
in general Matrix chats are really more like entire chat histories that
multiple people can edit and sync.</p>
<p>This makes Matrix a lot more familiar in functionality to old AOL/Google
chats, or things like Discord or Telegram, which people are used to and
find convenient. XMPP can indeed do all this, but it requires more
setting up, and you are more likely to run into unexpected things when
setting it up yourself.</p>
<h3 id="xmpps-advantages-over-matrix">XMPP's advantages over Matrix</h3>
<p>But all that said, as I said above, XMPP is better than Matrix.</p>
<h4 id="xmpp-servers-are-easier-to-manage-than-matrix">XMPP servers are easier to manage than Matrix.</h4>
<p>The default Matrix server software is atrocious. Trying to do something
&quot;simple&quot; like deleting a user account from the command line is
frustration. You might have to open up databases yourself and do it
manually. There is a distinct lack of configuration options in Matrix
compared to XMPP servers and XMPP server usually have a good
command-line interface to do basic things.</p>
<h4 id="xmpp-is-lightweight-matrix-is-big-bloatware">XMPP is lightweight. Matrix is big bloatware.</h4>
<p>I just logged into a VPS where I host both a Matrix and an XMPP server.
It has about 1G of RAM. Right now, <strong>27.7% of my memory is hogged by the
Matrix server</strong>, while <strong>the XMPP server is only using 1.4%</strong>. That
makes Matrix a major resource hog, while XMPP is the kind of thing you
can spin up on your already-existing VPS and not really have to worry
about it.</p>
<p>This is no big surprise because the default Matrix server is soyware
written in Python. While the Matrix team is allegedly working on a
better non-Python server-side, XMPP already has <a href="https://xmpp.org/software/servers.html">many different kinds of
server software to choose from</a>,
some of the more popular ones being
<a href="https://docs.ejabberd.im/admin/installation/">ejabberd</a> and <a href="https://prosody.im/">Prosody
IM</a>.</p>
<h4 id="matrix-is-less-decentralized">Matrix is less decentralized.</h4>
<p>This might be somewhat related to the above issue, but very few people
actually run their own Matrix servers and instead, just use Matrix.org,
which is the Matrix server of the official company. This means that
policies and blocks issued by Matrix the organization can functionally
disconnect who they want from most Matrix users.</p>
<p>Additionally, the default settings in the Matrix server configuration
use matrix.org and vector.im. These sites thus get a lot of independent
metadata from other unsuspecting instances.</p>
<h4 id="matrix-is-a-metadata-disaster">Matrix is a metadata disaster.</h4>
<p>It gets worse. Because Matrix doesn't really just exchange individual
messages, but because it syncs entire chats to all involved servers,
this means that while all messages might be end-to-end encrypted, the
conversation metadata is known to all servers, including what accounts
are involved, when messages are sent and other account information made
public (for example, users can add their emails and phone numbers to
their accounts). <a href="https://gist.github.com/maxidorius/5736fd09c9194b7a6dc03b6b8d7220d0">See more
here.</a></p>
<p>That means that all Matrix servers, <em>especially</em> Matrix.org, has a huge
repository of metadata. Although chats are thankfully encrypted,
encrypted chat logs are synced between all relevant servers, spreading
metadata far and wide, and nearly always back to Matrix.org.</p>
<p>Privacy with Matrix <a href="https://www.matrix.org/blog/2019/09/27/privacy-improvements-in-synapse-1-4-and-riot-1-4">used to be even
worse</a>.
Passwords used to be verified on a centralized identity server, and much
more.</p>
<p>You're probably wondering how any of this could get any worse...</p>
<p>   </p>
<p>...</p>
<p>   </p>
<p>Take a guess...</p>
<p>   </p>
<p>...</p>
<p>   </p>
<h4 id="-matrix-is-linked-to-israeli-intelligence-">🇮🇱 Matrix is linked to Israeli intelligence! 🇮🇱</h4>
<p>Matrix was developed and funded by a company Amdocs. Amdocs is an
Israeli company that has since moved to America and has near total
knowledge of American telephone communications.</p>
<p>You can read about the fun history of Amdocs
<a href="https://www.counterpunch.org/2008/09/27/an-israeli-trojan-horse/">here</a>.
More about Matrix and Amdocs
<a href="https://web.archive.org/web/20201219014215/https://samba.noblogs.org/post/2018/08/27/matrix-org-a-federated-app-funded-by-a-mossad-company/">here</a>.</p>
<p>Since American telephone records have &quot;mysteriously&quot; fallen into the
hands of Israel, there are many questions as how this has happened.
Perhaps this Israeli company which has had many Israeli military and
intelligence officers involved with it and which also has all American
telephone records might be involved?</p>
<p>Actually, this is just like Matrix. Amdocs does not have access to
telephone audio (so far as I know), they only traffic in metadata (when
calls are made and between whom). Matrix functions the same way. Chats
are <em>at least</em> end-to-end encrypted (which still puts this Israeli
honeypot lightyears ahead of proprietary spyware like Telegram), but
Matrix metadata is easily available to server administrators.</p>
<p>Now to be clear, formally, <a href="https://web.archive.org/web/20201104154843/https://github.com/matrix-org/matrix-doc/issues/979">since
2017</a>,
Amdocs no longer is the open sponsor of Matrix. It is instead funded by
a break-off organization called Vector. But Matrix/Vector has somehow
remained very, very well-funded for a &quot;community-driven&quot; project:
<a href="https://www.matrix.org/blog/2019/10/10/new-vector-raises-8-5-m-to-accelerate-matrix-riot-modular">they raised $8.5
million</a>,
that's a lot for free stuff! Crowd-funding for relatively unknown open
source software projects is apparently much more lucrative than I
thought!</p>
<p>(Of course, we all know that this is a baseless and widely deboonkted
anti-semitic conspiracy theory as Our Greatest Ally^®️^ Israel would
never do <a href="https://www.whatreallyhappened.com/WRHARTICLES/ussliberty.html">anything
bad</a> <a href="https://dancingisraelis.com/">to
us at all</a>.)</p>
<h2 id="in-conclusion">In conclusion</h2>
<p>Matrix is federated and free software which is end-to-end encrypted, but
it's bloated and the company behind it might be a privacy danger. Using
Matrix is indisputably better than using Telegram or Google or Facebook
on nearly every count, but XMPP outclasses Matrix on pretty much
everything.</p>
<p>XMPP is minimal software that is easy to run on a small server. It
requires more setup time and has the Linux-like &quot;problem&quot; of there
being a lot of &quot;fragmentation&quot; (i.e. choices), but XMPP is a much
better long-term tool despite the fact that it might require you to set
a couple more settings to get it how you want. XMPP is also more
scalable and customizeable.</p>
<p>I do run a Matrix server because I had to move some Telegram-using
friends to something better and I was worried that the world of XMPP
might be a little much. Retrospectively, I think I could've just
switched them to XMPP, and I might still in the future, but Matrix is
simpler for people to grasp and install if they don't know too much
about computers.</p>
<h3 id="how-the-xmpp-environment-can-be-improved">How the XMPP environment can be improved</h3>
<p>It would be very nice to have a cross-platform XMPP chat platform.
Obviously I don't want Electron trash like Matrix's Element (although
Element is intuitive enough), but when I say cross-platform, that might
just be several different XMPP clients (one Linux, one Android, one iOS,
etc.) that decide to go for similar design principles and branding. This
might sound stupid, but it makes the environment accessible to people
unfamiliar with it because they know that one program (or &quot;branding&quot;)
they can look up and recomend friends.</p>
<h3 id="other-note">Other note</h3>
<p>I suspect some people will be a little upset I &quot;only&quot; talked about
Matrix and XMPP as chat protocols. In reality, both are highly
extensible and can to many more things. I'll talk about that when I
feel it's relevant, but most people looking into them are looking for
an actually secure chat system.</p>


# Source:Luke Smith, URL:https://lukesmith.xyz/rss.xml, language:en-US

## Wanna Learn LaTeX?
 - [https://lukesmith.xyz/articles/wanna-learn-latex/](https://lukesmith.xyz/articles/wanna-learn-latex/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2021-02-12 00:00:00+00:00

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/animalibus.png" /></figure>

<h2 id="table-of-contents">Table of Contents</h2>
<ol>
<li><a href="https://lukesmith.xyz/rss.xml#intro">What is LaTeX?</a></li>
<li><a href="https://lukesmith.xyz/rss.xml#install">Installing LaTeX</a></li>
<li><a href="https://lukesmith.xyz/rss.xml#tutorials">LaTeX Video Tutorials</a></li>
</ol>
<p><strong>I have a full video tutorial series on learning LaTeX, broken into
small sensible parts,
<a href="https://videos.lukesmith.xyz/videos/watch/playlist/48a02be8-115a-4842-9ebf-6e3c6245f290">here</a>.</strong></p>
<h2 id="intro">What is LaTeX?</h2>
<p>Basically, it's how big boys write and format documents. Every public
brief, scientific article, book, cryptocurrency whitepaper or even
outline written by people who know what they're doing is written in
LaTeX.</p>
<p>If you want to see examples of documents made with LaTeX, you can see
<a href="https://lukesmith.xyz/dox/luke_thesis.pdf">my Master's thesis here</a> or <a href="https://lukesmith.xyz/dox/prelim2.pdf">another
paper here</a> that shows some diagrams and
other features you can have in LaTeX. Of course, LaTeX documents can be
infinitely customized.</p>

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/write.gif" /></figure>

<h3 id="is-it-hard">&quot;Is it hard?&quot;</h3>
<p>No. It's sort of like learning vim. People complain about how hard it
is until they take the bare minimum of time to learn it and realize how
much more effective they are with it. The return on investment is
massive. I wrote the thesis above in LaTeX in around a week of learning
from the bare minimum.</p>
<h3 id="how-is-latex-different">&quot;How is LaTeX different?&quot;</h3>
<p>LaTeX is a markup language, meaning that you write documents in whatever
text editor of your choosing and instead of manually moving margins and
placing things yourself, everything is optimally placed when you compile
the document into a .pdf.</p>
<p>Markup languages are great because they separate the task of writing
from the task of formatting. It's somewhat similar to the difference
between HTML (a markup language) and CSS (which does styling) and
Javascript (which does scripting). LaTeX does the equivalent of all
three, but it allows you to do them all separately so you can easily
extend documents.</p>
<h3 id="why-is-latex-better-than-microsoft-word-and-friends">&quot;Why is LaTeX better than Microsoft Word and friends?&quot;</h3>
<ul>
<li>Bibliographies are done <em>totally automatically</em>. For all the
research papers I've written in the past 5 years, I have never
written a bibliography page. You just tell LaTeX, &quot;Oh, APA style,
please&quot; and it's done.</li>
<li>Section/page numbering and cross referencing is done automatically.
That means if you refer people to a chart on page 52 multiple times
or figure 5 or chapter 4, then you move pages or figures or chapters
around, the references continues to refer to the page, figure or
chapter you originally meant. That also means you can literally copy
and paste text out of your document into a larger document and LaTeX
will automatically reconfigure all cross-referenced numbers to be
correctly referring to what you actually want them pointing to.</li>
<li>Text can easily be copied to a new format. I've written many term
papers that latter became monographs or books and with LaTeX, you
can just copy the raw text and it takes on the formatting of the
document it is inside of.</li>
<li>It is scriptable. You can use coreutilities and other programs to
search, modify and move text. This seems <em>useless</em> if you've never
done it, but it makes a world of difference when you realize you
can. You could use this, for example, to automatically take customer
information on your computer and automatically-generate professional
itemized invoices in LaTeX or the like. Also, being able to use
<code>sed -i</code> and <code>grep</code> with <code>.tex</code> files is fantastic.</li>
<li>For more advanced users, LaTeX is more than a markup language too:
and also has basic logic and tests (if statements and the like) that
allow you to react dynamically to unknown content.</li>
<li>You can write LaTeX in literally anything. I write it in vim for its
extensibility, but you can easily design your own workflow, instead
of having to rely on the ever-changing idiosyncracies of Microsoft
Word.</li>
</ul>
<h4 id="but-word-has-some-of-those-things">&quot;But Word has some of those things!&quot;</h4>
<p>Niche features that basically no Word-user uses. Also they change with
every new update. This is the primary operating structure of LaTeX.</p>
<h2 id="install">Installing LaTeX</h2>
<p>The core LaTeX package (<code>texlive</code>) is fairly small, but I highly
recommend you download <em>all</em> the LaTeX packages out there at the
beginning (a big download). This is nice because as you learn more
things, you won't have to manually download new packages. You'll be
able to experiment with new LaTeX abilities through new packages
seamlessly. Here's how you get them:</p>
<ul>
<li>GNU/Linux
<ul>
<li>Arch-based (Artix, Manjaro, Parabola):
<code>pacman -S texlive-most texlive-lang</code></li>
<li>Debian-based (Ubuntu/Linux Mint): <code>apt-get install texlive-full</code></li>
<li>Some distros (like Void) use <code>tlmgr</code> to install TeX packages
instead of the main package manager.</li>
</ul>
</li>
<li>Windows:
<a href="https://miktex.org/download/#collapse264">Here</a>.
(Choose the net install to be able to install all packages.)</li>
<li>MacOS: <a href="https://tug.org/mactex/">Here</a>.</li>
</ul>
<p>Once you've downloaded and installed that, you have a fully-featured
LaTeX engine on your machine! You can make lots of amazing things that
you don't even fully realize yet.</p>
<h2 id="tutorials">LaTeX Video Tutorials</h2>
<h3 id="basics">Basics</h3>
<p>First thing to learn is how to compile documents with <code>pdflatex</code> and the
basic principles of the TeX lanugage. In this first video, I talk about
how basic text, paragraphs, titles, headings and more work. This in
itself is enough to make a professional write-up.</p>
<details>
    Click to reveal video.


</details>

<h3 id="numbering-and-cross-referencing">Numbering and cross-referencing</h3>
<p>As you make more complex documents, you'll want to automatically number
and interrelate section, figure and other numbers together. LaTeX makes
this super simple, and make it even easier to copy your file into a new
file where it will automatically update all cross-referenced numbers.</p>
<details>
    Click to reveal video.


</details>

<h3 id="bibliographies-with-biber-and-biblatex">Bibliographies with Biber and BibLaTeX</h3>
<p>Bibliography management is a huge plus in LaTeX through biber. I
haven't written a bibliography in more than half a decade due to the
fact that LaTeX only needs a bibliography file of metadata and
autogenerates citations for any needed source.</p>
<details>
    Click to reveal video.


</details>

<h3 id="images-and-figures">Images and Figures</h3>
<p>TeX isn't all text either. You can insert and nicely format images in a
way that they are optimally placed without too much human interference.</p>
<details>
    Click to reveal video.


</details>

<h3 id="macros-to-make-things-easy">Macros to make things easy</h3>
<p>As you do more specific things, you might want to make your own macros
and functions. This really makes things easier, and you can do very
complex things very elegantly.</p>
<details>
    Click to reveal video.


</details>

<h3 id="slide-presentations-with-beamer">Slide Presentations with Beamer</h3>
<p>LaTeX isn't <em>just</em> for printable documents either. You can change your
document into a Beamer presentation, allowing you to present it as a
slide show similar to Microsoft PowerPoint's.</p>
<details>
    Click to reveal video.


</details>

<h3 id="making-a-professional-résumé">Making a Professional Résumé</h3>
<p>Here, I also give some extra pointers while I make a résumé.</p>
<h4 id="part-1">Part 1</h4>
<details>
    Click to reveal video.


</details>

<h4 id="part-2">Part 2</h4>
<details>
    Click to reveal video.


</details>

## Veganism Is the Pinnacle of Bugmanism
 - [https://lukesmith.xyz/articles/veganism-is-the-pinnacle-of-bugmanism/](https://lukesmith.xyz/articles/veganism-is-the-pinnacle-of-bugmanism/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2021-02-11 00:00:00+00:00

<p>People have quoted me as saying that. I forget where it comes from,
probably a livestream, but I definitely stand by it. Since a lot of
people labor under the assumption that my channel is about &quot;Linux,&quot;
I've accumulated a lot of subscribers that are variously nerds,
furries, degenerates, coomers, libertarians, communists, trannies and
among them are vegans. Some of them (I assume) are good people.</p>
<p>There's a stereotype about vegans that they are annoying and can't
talk about anything but Veganism. This hurtful stereotype comes from the
fact that it's true.</p>

<figure class="resright"><img src="https://lukesmith.xyz/pix/grill.gif" title="I just wanna grill!" /></figure>

<h2 id="bugmanism">Bugmanism</h2>
<p>Firstly, what is Bugmanism? How do Vegans fit the bill?</p>
<p>Long story short, a bugman is someone who rejects the purpose and role
of humans in their natural environment. They reject tradition, religion,
their family, gender roles, the expectation that a person should
contribute to their community, etc. They might do this for their
personal convenience (usually they just wanna coom outside of marriage)
or for apparently rational reasons, but the effect is the same.</p>
<p>If you want to sum up the esoterically evil goals of &quot;modernism&quot; or
whatever you want to call it, it is destroying the countervailing power
of tradition and in its place, new social engineers attempt to dictate
human values top down. If you separate people from their families, their
races, their traditions and <em>who they actually are</em>, you can engineer TV
shows, sports teams, activist movements and a million other things for
them to identify with and worship. <strong>Modernism pretends to liberate
people from arbitrary traditions and authorities, when in reality is
substitutes natural, emergent morals with controlled authorities.</strong></p>
<p>Veganism has always been one of the most radical examples of this logic.
Esoterically, <strong>Veganism forces one to abandon not just their own
traditions, but every human dietary tradition</strong> and leaves them at the
whims of processed grains and pharmaceutical supplements for a meager
survival.</p>
<p>That is, Veganism is highly disruptive: You can't have a normal life.
You can't have a normal meal. You can't wine and dine with people and
must make it an affair. You can't use traditional hand-made leather
products. You can't hunt or trap for food or raise animals, even for
eggs.</p>
<p>You become a nag at war with your family, the world around you. <strong>You
are trapped</strong> <em>within</em> urbanite bugman society: you can't even eat in
most non-urban places or foreign countries because the insane concept of
not cooking with animal fats and eating and using animal products just
doesn't exist. You have to survive holding your breath from one hipster
downtown area to the next.</p>
<p>On every point, you become more reliant on macro-society. Vegans try
very hard to give off &quot;organic&quot; vibes, but it's just a lie. Even
people on the internet who &quot;advertise&quot; their Vegan lifestyle spend
hours processing a basic meal and of course predigesting indigestible
plant matter with a blender. Try and find a non-urbanite Vegan in real
life. They exist, but they are an aberration.</p>
<h2 id="the-larp-of-vegan-for-health">The LARP of &quot;Vegan for Health&quot;</h2>
<p>Vegans sometimes pretend to advertise Veganism because it's allegedly
healthy. This is just public relations; any true Vegan, when you really
pin them down thinks that Veganism at its core is a moralistic belief.
Vegans are Vegans because they believe that not being Vegan is morally
deficient: killing/eating animals and using their bodies is bad. That's
it.</p>
<p>So you have your moral principle and run with it. What magical force
then is making that moral principle necessarily good for your health? If
Veganism <em>were</em> actually a good diet for humans, that would actually be
a massive coincidence. &quot;Vegans for health&quot; have to grapple with the
bizarre claim that meat, exactly the food that has been viewed in all
human cultures as superior and more desirable is somehow nutritionally
deficient.</p>
<h3 id="the-standard-american-diet-sad-is-plant-based">The Standard American Diet (SAD) is Plant-based.</h3>
<p>The weirdest thing is when Veganism is held in opposition to the
Standard American Diet, as if the American diet somehow represents
traditional or non-Vegan diets. <strong>The SAD is just Vegan-lite.</strong> SAD is a
post-Vegan invention of the diet industry take over the past decades has
been leading people into the most harmful parts of vegan diets: unstable
plant-oils, processed grains as meat substitutes, etc.</p>
<p>The pop-cultural idea of &quot;health&quot; is simply &quot;being skinny.&quot; Veganism
is <em>great</em> at making people skinny because it is slow moving starvation
(I have met some carbo-loading exceptions who fatten up).</p>
<p>Veganism is just to starvation what waterboarding is to drowning. If you
stick with it, you <em>will</em> eventually die, but it's so painful in the
meantime, you'll probably give up.</p>
<h2 id="veganism-is-rational">Veganism is rational.</h2>
<p>Vegans are exceptionally &quot;rational&quot; in that they adopt the moral
framework of modern society and follow it to its logical conclusion.</p>
<p>When you're given for your acceptance some inane religious platitudes
like &quot;equality&quot; and &quot;rights&quot; along with vaguely Marxist notions of
&quot;exploitation&quot; and &quot;slavery&quot; and &quot;oppressed classes,&quot; it seems
perfectly reasonable to expand that language to the relationship between
predators (humans) and their prey (many animals) (or maybe pets too).</p>
<p>If you're raised in a time of extreme moral nihilism except for not
liking the several historical events you're told that matter (usually
slavery and the Holocaust), obviously you're going to glom on to what
looks most like them: chickens in chains and sheep being led to
slaughter like sheep to slaughter.</p>
<p>Honestly, Veganism by their own logic might not be far enough. There is
some circumstantial research to the effect that plants have nervous
systems that might feel pain as well: you could go one step further and
simply eat nothing living. The [Ctistae]{.dfn} of ancient Thrace refused
to eat anything alive, eating only by-products/foodstuffs like milk and
honey. The Ctistae also refused to have sex, which might be something to
consider since Vegans eventually lose sexual function anyway.</p>
<h2 id="veganism-is-rebellious">Veganism is rebellious.</h2>
<p>Veganism has the same kind of &quot;rebellion&quot; that all other forms of
leftism share. It &quot;rebels&quot; against the system by perfectly
internalizing the system's values, extrapolating them to their logical
conclusions and thus fighting the system when it fails to meet those
obviously unworkable conclusions.</p>
<p>Corporations started shilling vegetable oils (which originally were and
frankly still are just industrial by-products) as workable replacements
for butter and lard. Seventh-Day Adventists lobbied for them because of
their own religion beliefs. Jews lobbied for them because they hate
unkosher lard. Years later, now we know that vegetable oils are highly
unstable and have contributed to the massive rise in heart disease.</p>
<p>Veganism is a leftist phenomenon. The psychological type of a leftist is
such that they will always subordinate their direct experience to
ideology. It doesn't matter if not eating meat or wearing leather or
using animal products sounds hard, their suffering is more proof of a
greater moral superiority.</p>
<p>Non-leftists can simply not become Vegans for longer than extremely
brief periods. Even if a Vegan wins an argument with them, a normal
person is just going to say, &quot;I'm sorry, I like animals and all, but I
can't not eat them, that's just crazy.&quot;</p>
<h2 id="veganism-only-makes-sense-in-a-bugman-environment">Veganism only makes sense in a bugman environment.</h2>
<p>Ask a vegan why he doesn't eat eggs. He will probably tell you a spooky
story about how terrible it must be for a chicken to live in a coop
laying eggs all day. That might even bring a tear to a sentimental
person's eye.</p>
<p>Out where I live, people have their chickens wandering in their yards
and garden pecking scraps. They return to their coops at night to be
safe from coyotes. Is there really something &quot;unethical&quot; in the mind
of a Vegan about picking up an unfertilized egg lain by one of these
chickens and eating it?</p>
<p>A lot of the moral logic behind Veganism falls flat outside of bugman
capitalism. Fundamentally, it's another manifestation of general angst
from lack of connection to the real natural world.</p>
<p>I say this because most Vegans are Vegans because they are softies who
have literally no connection to animals whatsoever until as a teenager
they watched a PETA documentary with chickens getting their heads buzzed
off or pigs walking around in their own poop.</p>
<p>Literally think about the animals. When wild animals die in nature, they
don't slowly slip away in the night surrounded by their family. They
die of starvation, or by being ripped apart alive by packs of coyotes.
Would you rather die by getting your brains blown out instantaneously or
die a &quot;natural&quot; death <a href="https://www.youtube.com/watch?v=Fg9_ZnojxmU">like
this</a>?</p>
<p>But to the original question, it really makes no sense even for a Vegan
to not eat or distribute the eggs a chicken lays... You're going to
have to get deep into Marxist analysis to think that's somehow
unethical. And once a chicken has living a long life of egg laying, why
not quickly and painlessly <a href="https://poultrykeeper.com/general-chickens/how-to-kill-a-chicken/">dislocate its
neck</a>
and eat it for dinner? If you don't, your cat will eventually gore it
and it'll be a mess.</p>

<figure class="resright"><img src="https://lukesmith.xyz/pix/kill_chicken.gif" title="Boomer attempts to kill chicken." /></figure>

<h2 id="animals-live-to-be-eaten">Animals live to be eaten.</h2>
<p>This isn't even a metaphysical claim. Domesticated cows and pigs and
chickens do not and cannot live as they exist in the wild. They have
evolved symbiotically with us as sources of food. They can go feral and
breed with wild boar and the like, but their composition is based on
their domesticated state.</p>
<p>Wild game like deer have lived alongside human hunters for centuries.
Their breeding habits and evolutionary development is based in the fact
that a <a href="http://archive.jsonline.com/sports/outdoors/study-sheds-light-on-top-causes-of-deer-mortality-b99190938z1-241992741.html">sizeable
portion</a>
of their population will be hunted by humans every season.</p>
<p>If you actually care about &quot;the environment&quot; (1) you would care for
humans, whose natural diet is meat and (2) you would be terribly worried
about the unintended consequences of severing one of the most important
links in the food chain.</p>
<h2 id="dumb-vegan-sayings">Dumb Vegan sayings</h2>
<h3 id="you-wouldnt-kill-it-yourself">&quot;You wouldn't kill it yourself!&quot;</h3>
<p>They say this whenever someone turns their eyes away from an animal
being killed in one of their Vegan propaganda videos.</p>
<p>Guess what, I also might turn away if I see a video of a sanitation
worker wading through human feces it in a sewer. That doesn't mean that
I'm a hypocrite for taking dumps in a toilet connected to city sewage.</p>
<p>I turn away when I see depictions of amputations of gangrenous limbs in
movies too. That doesn't mean I don't think it's not medically
necessary.</p>
<p>Killing animals is actually a bad example of this because while all
cultures are disgusted by feces and amputations, in most times and
places (including this country before Bambi), killing animals was
nothing any self-respecting grown man would react to. It goes without
saying that there are many countries where people recreationally torture
dogs and cats.</p>
<p>I don't say that to say that I'd be okay with killing dogs and cats,
merely that the trained moral responses we have for them are very
localized and subjective in our own modernist viewpoint. But Millenials
have now been raised in a Disney fantasy-land where animals think and
talk like us and therefore must share the same feelings. Vegans absurdly
&quot;imagine what it'd be like&quot; to live in industrial farming as if a
chicken's birdbrain is having an existential crisis while living in a
cage.</p>
<h3 id="veganism-is-minimal-or-more-self-sufficient">&quot;Veganism is minimal or more self-sufficient.&quot;</h3>
<p>Vegans have been fruitlessly trying to meme this one on me for forever.
Starvation and death is minimal, I suppose, so it is at least true in
that sense. <strong>Veganism is ultimately the diet of only eating inedible
garnish that looks &quot;good&quot; on Instagram.</strong></p>
<p>Raising most animals is easier and more efficient than raising
vegetables. If it's too hot, potatoes don't naturally know to go move
to the shade. Yams don't eat your overgrown grass. Onions don't poop
out fertilizer. Tomatoes can't pull a simple tractor. You can't skin
dead okra and make leather out of it. You can't grind up old mustard to
make bonemeal (that's not just something in Minecraft, by the way).</p>
<p>Animals are an absolutely necessary portion of any homestead in life and
death. Listen, I like growing stuff. I like growing vegetables. But
vegetables are just not real food... They are garnish. They are sides.
They are only enjoyable insofar as they elevate your enjoyment of real
food: meat.</p>
<h3 id="veganism-is-more-efficient-or-environmental">&quot;Veganism is more efficient or environmental.&quot;</h3>
<p>People say that eating plants is more &quot;efficient&quot; because they saw an
energy pyramid diagram as a kid, which shows how many prey animals are
needed to maintain carnivorous animals. If we actually lived in a place
where there was a calorie shortage, like a desert planet where greens
couldn't grow, that might be an issue. It frankly just isn't here.
We're not exactly running out of grass to feed cows. Most people are
mowing their grass and throwing it away.</p>
<p>There are people who make really absurd environmentalist arguments
against meat as well, for example, methane from cows warms the globe.
Okay. Fine. So what does Veganism do about that? Are Vegans going to
kill the cows for us? Should we just let them starve in the woods since
we can't harvest them for meat or even milk? What about all the game we
won't be hunting? Those 50% of deer annually that we won't be
killing&mdash;won't they me causing pollution with the huge amount of
calories they need to frolic in the woods all days? Same will all other
game. Most of those arguments are cute just-so stories and they fall
apart after examination. Anyone can play that game.</p>
<h2 id="lets-just-laugh-at-this-for-a-minute">Let's just laugh at this for a minute...</h2>
<p>Alright class, look at this commonly posted vegan meme and tell me why
it's retarded:</p>

<figure class="titleimg"><a href="https://lukesmith.xyz/pix/vegan_protein.jpeg"><img src="https://lukesmith.xyz/pix/vegan_protein.jpeg" /></a></figure>

<p>&quot;Per 100 calories&quot; shows a deception so insane you should laugh.
Whoever made this image wants you to <em>believe</em> that the piece of steak
on the fork is equivalent to the tiny broccoli head on the right.</p>
<p>You can compare the nutrition of both
<a href="https://www.calorieking.com/us/en/foods/f/calories-in-fresh-or-dried-vegetables-broccoli-raw/uhZAljTASPuU9YnkyCZdFA">broccoli</a>
and
<a href="https://www.calorieking.com/us/en/foods/f/calories-in-beef-ground-beef-80-lean-20-fat-pan-browned/MJPo9HnUSnGiV2-9eBsCBw">beef</a>
at those links yourself.</p>
<p><strong>In order to get the protein in a single large bite of steak, you'll
have to eat more than half a pound of broccoli.</strong> Good luck. Now you
know why those poor impressionable girls who go vegan bloat up. And
that's only 100 calories. 2000 calorie diet? Have fun. If you're
famished, it's pretty easy to eat a big steak with 2000 calories
(around a pound and a half of matter) and it will fill you up without
any bloating or stomach pains. You'd have to eat <em>twelve pounds</em> more
or less of broccoli or equivalent greens for that. And with all that
fiber, you're going to just be pooping it all out.</p>
<p>Honestly, the human disgust response will stop you way before that.
It's easy to eat a juicy steak without or without sauce, salt and
pepper, but you'd nearly have to put a gun to someone's head to make
them eat their daily 13 pounds of indigestible garnish.</p>
<h2 id="noootruits-dont-actually-matter-anyway">Noootruits don't actually matter anyway</h2>
<blockquote>
<p>&quot;Plants don't have over fifteen micro-nooootrients...&quot;
&mdash;<a href="https://www.youtube.com/user/TheGenreDoesntMatter">sv3rige</a>, at
the end of every video</p>
</blockquote>
<p>A lot of Vegan autism gets focused on replicating the consumption of
known nutrients and minerals using only plants. The image above, in
addition to being deceptive is based on a flawed idea that human
nutruition is about <em>consuming particular amounts of particular
substances</em> as if we are a perfectly predictable machine or a videogame.
This <strong>isn't just a Vegan problem</strong>, basically everyone implicitly has
this idea.</p>
<p>The reality is that those nutrients on the Nutrition Facts are a narrow
realm of what might actually be relevant for the complex organ of our
bodies. Additionally, there are many types of proteins and vitamins and
minerals that the back-of-the-box doesn't account for. The Vegan game
of saying, &quot;we can get that too&quot; is utterly pointless when you realize
we have nowhere close to a full idea of how the human body works, only
some plausible theories about the relationships between certain
nutrients and what they seem to do. As in the case of some nutrients,
like the falsely-maligned cholesterol is a good example of something two
generations of people were told to fear and reduce only for us to later
realize that our ideas about how it interacted in the body were arguably
literally backwards.</p>


# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## You don't NEED the command line to use Linux, but you SHOULD use it!
 - [https://www.youtube.com/watch?v=aiPthUAIYBg](https://www.youtube.com/watch?v=aiPthUAIYBg)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-10-12 00:00:00+00:00

Get your Linux desktop or laptop here: https://slimbook.es/en/



This thing is often considered as much an argument FOR the use of Linux, as an argument AGAINST it. Power users can't live without it, beginners are scared of it, and people who never used Linux are convinced it's needed just to run a program. 


👏 SUPPORT THE CHANNEL:
Get access to an exclusive weekly podcast, vote on the next topics I cover, and get your name in the credits:

YOUTUBE: https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Patreon: https://www.patreon.com/thelinuxexperiment

Or, you can donate whatever you want: https://paypal.me/thelinuxexp?locale.x=fr_FR

🏆 FOLLOW ME ELSEWHERE:
Join us on our new Discord server: https://discord.gg/xK7ukavWmQ
Twitter : http://twitter.com/thelinuxEXP
My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw
Follow me on ODYSEE: https://odysee.com/@TheLinuxExperiment:e
Or join ODYSEE: https://odysee.com/$/invite/@TheLinuxExperiment:e

📷 GEAR I USE:
Sony Alpha A6600 Mirrorless Camera: https://amzn.to/30zKyn7
Sigma 56mm Fixed Prime Lens: https://amzn.to/3aRvK5l
Logitech MX Master 3 Mouse: https://amzn.to/3BVI0Od
Bluetooth Space Grey Mac Keyboard: https://amzn.to/3jcJETZ
Logitech Brio 4K Webcam: https://amzn.to/3jgeTh9
LG Curved Ultrawide Monitor: https://amzn.to/3pcTVDH
Logitech White Speakers: https://amzn.to/3n6wSb0
Xbox Controller: https://amzn.to/3BWmIA3
*Amazon Links are affiliate codes and generate small commissions to support the channel*

00:00 Intro
01:24 Refresher on the terminal
02:31 Why you don't NEED the command line
05:02 Why you SHOULD use it
08:40 Parting Thoughts


Why you don't NEED the command line

So, let's begin with why I think you don't NEED the command line. Don't worry, I'm not saying it's obsolete, or that it's useless. I'm just saying that most regular users can use a Linux desktop without touching it.

From the software stores, to the graphical package managers, to the driver install utility, linux kernel update utilities, graphical ways to add new repositories, virtually anything you might want to install has a graphical utility, at least if you use one of the major desktop environments.

If you want to install something that's not in your distribution's repositories, there again, the command line isn't needed.

And sure, if you encounter an issue, most of the tutorials you'll find on the internet will tell you to use a command line to change something, or install something. But you could also have done so using a graphical tool, it's simply easier to write a tutorial using the command line than to have detailed guides for all Linux desktops environments.

Why you SHOULD use the command Line

Now let's see why you SHOULD use the command line.
Ok, maybe not SHOULD: you don't have to, if you don't want to. But the command line on Linux can make things really easier if you have multiple repetitive tasks that you want to do.

Let's say, for example, that you just setup your Linux system.

Let's say you want to install all your programs. Graphically, you'd have to search for each of them individually, click install on each of them, and then wait for them to install one by one.

With the command line, you could install all these programs with just one line.
On Ubuntu or Ubuntu based distros, for example, you'd type

sudo apt install

and then the names of all the programs you want to install separated by a space.

You could also add to that command all the non-graphical packages you'd like to install: drivers, codecs, fonts, background services...

But there's a LOT more.

An app crashes when you open it? Start it from the command line to get the error messages and see what could have gone wrong and get some help on the internet.

Has your computer frozen and you can't use your mouse anymore? Type Control + Alt +F1, F2, F3, up to F7, to get into a terminal, and type reboot to restart your computer.

See, you can create shell scripts. These let you run commands one after the other, and even introduce conditions to do specific things depending on specific events.

For example, if you tend to install the exact same applications and packages each time you reinstall your favorite distribution, you could create a script that has the install command we talked about before.

Some apps you usually install aren't in the repos and you always have to go hunt for them online? Add a line to download the necessary file and install it, right from the same script.

You could also find how to change various settings through the command line and add them to your script so each time you reinstall, you just run that script once and you're all set up.

Do you run different distributions on different computers? You could have a single script to install all your programs, packages, and settings, on any distro you usually use, using if conditions. Just detect which distro you're running the script on, and make it run the right command for this distribution.


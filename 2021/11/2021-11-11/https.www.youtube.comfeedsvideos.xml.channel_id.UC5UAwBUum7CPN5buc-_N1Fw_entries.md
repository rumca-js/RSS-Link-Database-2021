# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## JingPad Roadmap and updates, installing other distros, open source status, pen latency, and more
 - [https://www.youtube.com/watch?v=Vj3QueLJfSY](https://www.youtube.com/watch?v=Vj3QueLJfSY)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-11-11 00:00:00+00:00

Wanna get your own Linux server? Visit https://www.linode.com/linuxexperiment for a 100$ credit ! 


Get your Linux desktop or laptop here: https://slimbook.es/en/

👏 SUPPORT THE CHANNEL:
Get access to an exclusive weekly podcast, vote on the next topics I cover, and get your name in the credits:

YOUTUBE: https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join
Patreon: https://www.patreon.com/thelinuxexperiment

Or, you can donate whatever you want: https://paypal.me/thelinuxexp?locale.x=fr_FR

🏆 FOLLOW ME ELSEWHERE:
I also do a Gaming Podcast: https://www.youtube.com/channel/UCbRPZ11S1quJ4ESoj42A3ug
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
00:29 Sponsor: Linode
01:41 JingPad / JingOS Roadmap
06:23 JingOS 1.1 Update
08:46 Installing other distros, pen latency...

Ok, let's begin with the roadmap for this device: fortunately, it's not a ship it and drop it product, the company behind it, JinGLing, has published a first roadmap for the near future with various important milestones.

So, we already went through the "Major event of JingOS", which I guess is the release of JingOS, we also already got the JingOS ARM 1.1 update.

The code for the ARM version isn't available yet, and this is the goal of that project. More interesting is the availability of Android App Support on November 14th. It's of course, a pre-alpha version, probably on the same level as what they've demo-ed on their videos previously, or what we've already seen from other youtubers with review units.

Now, the next item on the roadmap is also a major one, which is "Bootloader unlock".
At the moment, you can't install other distributions on the JingPad. JingOS is the only one that will run, because the bootloader isn't unlocked and isn't accessible.

Next, we have a JingDroid ROM, which is just a JingOS Android ROM, that's closed source, and can be installed on other Android devices. We should also see an Ubuntu Touch Port for the JingPad.

And finally, at the very end of November, on the 30th, they should release a JingOS ARM ISO, that people can try out on other devices.


Ok, now Let's talk about the latest update to JingOS ARM on the JingPad. It was released just a few days ago, and I installed it on my device.

The main ones are related to energy consumption and charging speed, which were 2 big issues with the JingPad: it discharged extremely quickly, and charging was extremely slow as well.
I can report that this is now fixed. Sorta.

In terms of applications, the Jing OS Store now loads a lot faster, and it got a few more apps compared to the last time I showed it, including Okular, Rhythmbox, VLC, Kodi, Krita, or MyPaint.

The apps that are added aren't specifically optimized for touch: VLC has super tiny controls, Okular has its super small menu bar, for example.

Apart from that, you now have access to the full menubar for Konsole, the terminal app, and it's correctly sized as well.

The File manager also gained some progress indicators when copying and moving files.

On the hardware acceleration front, I thought it wasn't enabled, but after using mesa-utils and glxinfo, it seems that it is, which is disappointing: performance and smoothness is not what I'd expect from something using the GPU to render the animations.

On the kernel side of things, JingOS ARM doesn't run on a mainline Linux kernel. Uname returns a Linux JingOS 4.14 kernel, but it is actually an Android kernel for now.

Speaking of other distros, as mentioned previously, you can't install them yet.

I was also asked about Telemetry in the OS. The x86 version collects the MAC address of the device at the time of activation, at first boot, and it seems that the ARM version can also collect the country of the user, their timezone, and automatic bug reports, but only IF you enabled "privacy sharing" at first boot when setting up the device.

People also asked me about the pen latency, I wouldn't recommend this in its current state for anyone who wants to use this as a drawing tablet. Using Krita, for example, is pretty stuttery, and there is no palm rejection builtin these apps, or the tablet, so you tend to draw lines with your hand as well.


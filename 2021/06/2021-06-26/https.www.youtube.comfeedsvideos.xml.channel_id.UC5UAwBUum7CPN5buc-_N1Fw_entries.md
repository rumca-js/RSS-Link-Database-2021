# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Pop!_OS 21.04 - Cosmic, or less than Stellar?
 - [https://www.youtube.com/watch?v=y-uUv1jkKOQ](https://www.youtube.com/watch?v=y-uUv1jkKOQ)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-06-26 00:00:00+00:00

Download Safing's Portmaster for FREE and take control of your network traffic: https://safing.io/portmaster

Today, we're going to take a look at PopOS 21.04. Or 21.06? It should release in June, so 21.04 doesn't really make sense, right? Anyway, the guys at system76 have been working at their distro for a while now, but this release is the first time that I felt they departed from baseline Ubuntu enough to warrant a dedicated video. So we're gonna take a look at the new stuff, but also at stuff that already existed previously, as it's the first time I'm really using PopOS at all, and the first contact I'll get with their GNOME redesign called Cosmic.

Infinitely Galactic's Channel: https://www.youtube.com/user/InfinitelyGalactic

Become a channel member to get access to a weekly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on ODYSEE: https://odysee.com/@TheLinuxExperiment:e
Or join ODYSEE: https://odysee.com/$/invite/@TheLinuxExperiment:e

## Install process
The first contact you get with PopOS is also the first departure from Ubuntu: they don't use the Ubiquity installer, they use the installer created by the guys at elementary OS. Actually, PopOS has been using that new installer even before elementary OS used it themselves.

The installer opts for a "first run setup", which means that user account creation is handled after the install is complete.

## Cosmic Desktop

First, you don't get a unified "Activities" view, instead, you have 2 buttons: one for workspaces, and one for Applications.

The Workspaces view displays your open windows and your workspaces on the left. It's basically what the activities view is on GNOME, except having the workspaces on the left makes it easier to just slide your mouse down from the "workspaces" button into the list of workspaces. You'll be able to change that behavior as well, to put the workspace list on any other screen edge if you prefer.

The Applications button shows the Applications grid, with all the latest GNOME goodies,  like folder creation and renaming, or reordering the applications in the grid.

Cosmic also adds a permanent dock on the bottom of the screen. Its default configuration is... not great. It doesn't autohide when a window is maximized, and it extends all the way to the screen edges, which doesn't really serve a purpose. You can change both of these behaviors in the settings, with plenty of other options, like the size, the position, or the ability to hide some of the default launchers.

While it serves as a launcher for apps, and for task management, you can't minimize an app by clicking on its icon.
The rest of the layout is standard gnome, with the date and time in the middle of the top panel, and the indicators to the right.

Now, that new launcher. This is a brand new addition to PopOS 21.04 as well. It can be summoned by clicking its dock icon, or by pressing the super key, although, once again, that behavior can be changed.

The launcher is a bit lackluster at the moment. It only lets you search for applications, or open windows, and do calculations if you press the "equal" symbol first. It's supposed to let you execute commands, but I couldn't get it to run Xkill, or top, or any other command I tried.

The problem is that in GNOME, system wide search is handled through the activities view. Here, that search only appears in the applications view, and it doesn't search through the system either, unless you manually re-enable these search options in the settings. But enabling all these search providers doesn't do anything for the launcher, which doesn't seem to take advantage of them.

Basically, PopOS has, by default, made search worse than in GNOME, which isn't fantastic, and the launcher, as of now, doesn't bring any benefit compared to the system-wide search that GNOME offers by default when pressing the super key and typing. It's a bit disappointing, especially considering that there are way better programs that do that already, like ULauncher.

In general, that new Cosmic desktop layout just doesn't seem to bring much that's new, and it kinda feels like it's not finished. It might be a good foundation for a more refined version of GNOME in the future, but in this current incarnation, it offers less functionality out of the box in terms of search, the dock doesn't seem completely fleshed out yet, and separating workspaces and applications doesn't really bring any advantage apart from being more legible to complete newcomers to Linux and GNOME.

So I hope to see Cosmic mature in the future.


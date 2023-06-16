# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Why are app developers porting to Apple Silicon and not to Linux?
 - [https://www.youtube.com/watch?v=TaX5Se8bV90](https://www.youtube.com/watch?v=TaX5Se8bV90)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-07-09 00:00:00+00:00

The first 1000 people to use the link will get a free month of Skillshare Premium Membership: https://skl.sh/thelinuxexperiment07211

Get your Linux desktop or laptop here: https://slimbook.es/en/

Today we're going to address something that is regularly pointed out to me in the comments: why would third party application developers go through all the trouble of porting their apps to Apple Silicon, which is a whole new architecture, and not do a port for Linux, which runs mostly on x86 CPUs, same as what Macs and Windows computers generally run up to that point

Become a channel member, or a Patreon Member to get access to a weekly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on ODYSEE: https://odysee.com/@TheLinuxExperiment:e
Or join ODYSEE: https://odysee.com/$/invite/@TheLinuxExperiment:e

00:00 Intro
01:29 Market Share
02:38 Developer Tools
04:27 App Distribution
07:45 The elementary exception
09:47 Parting Thoughts

The first main reason for developers taking the time to port their apps, is market share. But wait a minute, Apple might be very present in the US, but in the rest of the world, Macs just aren't all that common. 

According to StatCounter, Windows still holds 73.5% of the market, with Mac OS commanding 15.87%. That's small, but it's still a lot higher than Linux on the desktop, which only holds 2.38% marketshare.

So, obviously, as a developer, if you look at these numbers, you're going to invest time porting your app to the new Apple platform, and not to Linux.

Second reason is developer tools.

Apple is known for restricting what they allow on their platforms, but they also have very good developer tools. They have their own IDE, Xcode, their preferred programming languages, with Swift and Objective C, and they have tons and tons of online resources and documentation to help you get started.

There is no "standardized starter kit" on Linux that would give you a quick and easy starting point. You have to pick between the language you want to use, between GTK or Qt, or Clutter, or something else, and then find some tutorials and documentation by yourself, and get coding.

Apple has simple guides and checklists to help you look at what you need to take care of, when you start porting your app to their new architecture. it's a guided process, and you can keep using the tools you were already using: same language, same IDE, same compilation process.

I think it all comes down to the process: on the Apple platform, you have a very straightforward path, you're guided every step of the way. You're more limited, and you have to pay to distribute, I think it's 99$ per year to get access to the developer tools, but at least you know where you're going.

On Linux, you have to make conscious choices along the way, every step of the way. It's a "do it yourself" process: you need to look for, and learn on your own, as there is no standardized development platform.

Third reason? Application distribution.

Distributing your app is crucial to ensure that people will find it, download it, try it, use it, and maybe pay for it. Apple has that pretty much in the bag.

The Mac App Store might not have everything that you can install on your mac, but it's still another standardized process. You have an online developer console, where you upload your app, enter the details, submit it for review, make changes, upload updates, whatever.

If the mac app store rejects you, or if their limitations don't fit your app, you can still distribute it through your own website, you only have 1 binary to provide. Macs only have 1 packaging format, all applications are .app, which is basically a folder containing the executable and its required libraries, basically like an AppImage.

On Linux, distributing your app is a LOT more convoluted.

First, you need to have packages separated for each architecture: x86 or ARM for example. That's 2 compilation to do, 2 packages to maintain.

Second, you'll have to choose the packaging format. If you only do a .deb, your app won't work on Fedora, Red Hat, openSUSE, or Arch based distros.
If you do an RPM, you lock yourself out of Debian, and all ubuntu based distros.

You could do a flatpak, or a snap, but not all distros use these, even though Flatpak is virtually everywhere now, and some users don't like these packaging formats and won't use them.

Then there is the fact that only ONE app store on Linux lets you ask for money for your app, that's the elementary AppCenter. Anywhere else, you can't charge users for downloading the app, so you have to implement some kind of licence key system, or subscription system, that you have to handle all on your own


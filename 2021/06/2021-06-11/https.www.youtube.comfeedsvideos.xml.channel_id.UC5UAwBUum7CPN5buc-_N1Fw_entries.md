# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Think XFCE looks bad? Think again! - XFCE Customization
 - [https://www.youtube.com/watch?v=BL49b-u7ucQ](https://www.youtube.com/watch?v=BL49b-u7ucQ)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-06-12 00:00:00+00:00

Use awesome Linux servers and get a 100$ credit on your new Linode account: https://www.linode.com/linuxexperiment

For as long as I've used Linux, I've heard, and thought, that XFCE was a "bad looking desktop". While my first contact with it didn't really change my mind, it's time to take a look at how to change its look and feel, and hopefully get rid of that preconceived notion. We'll start with a few examples of changes applied to XFCE by some distros, and then we'll try to build our own look and feel.

Become a channel member to get access to a weekly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on ODYSEE: https://odysee.com/@TheLinuxExperiment:e
Or join ODYSEE: https://odysee.com/$/invite/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

Ok, so let's start with something that's really close to the default: Xubuntu. Xubuntu doesn't change much from the default XFCE layout: they keep the top bar mostly intact, and they remove the bottom panel with its quick launchers.

They swapped out the default XFCE Menu for something people have been recommending quite a lot: the Whisker menu. When you right click it, you get access to a LOT of options to really make it your own: you can display apps as icons instead of lists, elect to show the "generic app names".

On top of that, the whisker menu lets you change where the category list is displayed, where the search field goes, and a lot more.

Apart from that, Xubuntu doesn't change much: the default theme is Greybird, and the default icons are the elementary XFCE ones.
For a good close to vanilla XFCE experience Xubuntu seems perfect, but that's not what we're looking for here.

Let's move on to Linux Mint. Mint tweaks their XFCE implementation to look and feel exactly like Cinnamon, their main desktop, and it's quite nice.

They basically move the top panel to the bottom, in a more windows-like layout, and they also use the whisker menu, which apparently you can resize. Mint also got rid of that second panel that default XFCE ships, to integrate its features in the main one, namely the quick launchers.

The rest of the layout is pretty much bog standard, with the window list, and the system tray applets.

In terms of look and feel, Mint brings its own green appearance, with the Mint-Y, or Minty GTK theme and icons, and going over to the Ubuntu fonts instead of the Noto family.
Still, that's a simple customization effort, it's basically a new theme for everything, and flipping the top panel to the bottom. We can go further than that.

## Pick and choose

This is Enso OS, and honestly, if you had told me it was based on XFCE, I just wouldn't have believed you initially.

The layout is nice: you have a dock, and a top panel with a global menu. On top of that, you get the regular system tray applets, but with a better calendar than the default.

The bottom panel isn't an XFCE panel at all, it's the Plank dock, aligned to the left of the screen. It hosts an application launcher that looks pretty cool and can be invoked with the "super" key, a "multitasking" icon that opens the multitasking view that elementary OS users will be familiar with, and there are also some quick launch shortcuts.

Speaking of elementary OS, Enso OS uses their window manager, which means that you also get animations when minimizing, maximizing, and tiling windows. It looks pretty good.

Enso OS also changes the theme for their own, the icons using the "Paper" theme, and uses the Ubuntu fonts, and the Breeze cursor theme that KDE Plasma created.

## My own results

So, I moved the panel to the left. I added Whisker menu, and configured it to be pretty much just an applications list: I only use the menu as a search engine, and as such I don't need fancy icons or categories, just a nice list of apps.

Then it's a separator in expanded mode, and pretty much the standard notification applets, clock, and logout menu.

On the bottom left, I used Plank, the dock elementary OS uses, because it's fast, it's super simple, and it handles window management. I decided to go without a border around icons, and to group everything on the left, to make mouse operations easier.

The theme I used is called Qogir, for the GTK theme, the window borders and the icons, I think it looks quite good, and I already use it as a backup theme for GTK apps on my KDE desktop.

I moved all window buttons to the left, except for the maximize one, because I like trying new stuff out, and I changed the font to Inter, because it's a lot more professional looking than Noto in my opinion.


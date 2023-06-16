# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## KDE Plasma 5.21 - New look, new menu, and Wayland 100% usable
 - [https://www.youtube.com/watch?v=qbAuxp_I0zk](https://www.youtube.com/watch?v=qbAuxp_I0zk)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-02-13 00:00:00+00:00

Visit​ https://www.linode.com/linuxexperiment for a 100$ credit on your new Linode account! 

Plasma 5 continues its release cycle, and we are days from the release of Plasma 5.21, a pretty big release if we compare it to the ones that came before. On the menu, we have a bit of a redesign, a new application menu, manu, many wayland improvements, and a whole new system monitor.

Become a channel member to get access to a weekly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

The desktop is what received the most attention this time around. It's good to see KDE focusing on the user experience of the actual desktop instead of refining the settings, even though that work was necessary and welcome.

To being with, we have a new look for titlebars and windows. Where before, the titlebar was dark and separate from the contents of the window, now the titlebar blends with the menu bar, and the toolbar, in a grey, solid background.

Now, for users who like having their windows light themed, but prefer their panels and widgets a bit darker, KDE ships the Breeze twilight theme by default, which keeps the default light color in the application windows, but puts all plasmoids into the breeze dark theme.

The other important change here is the new application menu.
This new menu also offers quick system actions, like sleep, restart, shut down, or log off, right from the bottom.

There is also a new media applet, that shows tabs for every audio source that you have, so you can control all your audio playback through one single applet, without having one for each app you usually interact with.

Finally, the Sound applet now displays the main microphone's volume.

## The Apps
Now let's move on to the applications. The core Plasma apps haven't changed much here, but there is a whole new arrival: a new system monitor.

This won't revolutionize the way you use your computer, but it's still a nice tool to have when you need it. The old KSysGuard is out, and the new System Monitor tool is is, then, with a modernized interface.
It's actually based on the recent plasmoids for system monitoring, which means it looks good, and it's very flexible.

The settings still see some changes, as the effort to revamp and make these look more coherent continues. First, there is a new Firewall configuration page, to configure UFW or Firewalld. It's a simple page, but efficient, and it lets you quickly create rules if you need them.

A few other pages have also been revamped and made to look more in line with the rest of the settings, including the Accessibility page with a list of options and a side panel to configure them, the Desktop Session options and the login manager, which now looks more like the other "appearance" settings, with a list of available themes.

## Wayland
Now the last main part of the efforts for Plasma 5.21 is Wayland. 5.20 had already done a lot of groundwork here, but 5.21 is probably the release that makes KDE shine on it.

As a matter of fact, this whole video has been recorded on the Wayland session of KDE 5.21, on KDE Neon Unstable.

First of the changes is the latency: compositing has been improved a lot, and there should now be a lot less latency betwen an action and its result on the screen. This can come at the expense of smoothness of animation, so you even get to change the balance that you want to reach, right in the compositor settings, with a few options ranging from the lowest latency, with the possibility of dropped frames, to super smoothness, which will increase the daly between your action and its result, but will look super slick.

KDE also added the ability to use mixed refresh rates display configurations, so you can now use your main display at 100 or 144hz, and a secondary one at 60hz without issues.

Krunner is also able to accurately list all open applications on Wayland now, so it should be a lot more useful, and support for GTK4 applications has been implemented as well, as the new version of that toolkit has some changes specifically for Wayland.

Touchscreen users will also have better support for the virtual keyboard, especially when using GTK applications, which should now more reliably make the keyboard poip up when needed.

Finally, there are the first steps towards implementing multi-GPU support in Wayland, so let's hope it will make dual GPU devices more usable.


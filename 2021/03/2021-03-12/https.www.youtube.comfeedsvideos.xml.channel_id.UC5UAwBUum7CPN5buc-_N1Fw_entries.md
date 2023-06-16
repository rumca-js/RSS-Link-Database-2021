# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Can you REPLACE CHROME OS with this Linux distro that runs ANDROID APPS?
 - [https://www.youtube.com/watch?v=ugAB_ug9MZg](https://www.youtube.com/watch?v=ugAB_ug9MZg)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-03-13 00:00:00+00:00

The first 1000 people to use the link will get a free trial of Skillshare Premium Membership: https://skl.sh/thelinuxexperiment03211

Chrome OS has been getting more and more popular, as chromebooks prices are relatively low, and many people just need a browser to work. But this system is still completely owned by Google, tied into their services, and as such, not very private. FOrtunately, there is an alternative on the horizon, and it's called Ubuntu Web Remix. let's see if it's actually ready to replace Chrome OS

Become a channel member to get access to a weekly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

This video is sponsored by Skillshare.

## The Interface
- Uses GNOME-Shell, with the dash2panel extension to mimic what Chrome OS looks like
- It has a main menu, a favorites list, date and time indicator, and the regular system stuff
- It uses the Adapta theme and the papirus icons
- It all give it some kind of older Android look and feel, but it's not unpleasant
- The GNOME shell doesn't seem themed at all

## The apps
- Very minimal installation by default:
- only a few web apps, a local file manager, Nautilus
- An archive manager, calculator, document scanner, and screenshot tool, plus the GNOME settings. You also have the system monitor, and GNOME boxes for some reason
- No GNOME software, but you have a terminal, so you can install it
- There are a bunch of webapps preinstalled though, including all the /e/ services
- /e/ has online services based on Nextcloud, including cloud storage, but only 1Gb of it, a calendar, a contact directory, en email address, notes, photos, and tasks
- All of these apps will just take you to the corresponding tab in your /e/ nextcloud account, that you can create directly by launching any of these apps
- If you don't want to use /e/ services, you can decide not to use them, or remove them
- There is a super simple tool to let you remove installed web apps. it's not pretty, but it works
- You also get Firefox, of course, which is the base for all of these webapps, as they'll open in a Firefox window, without any of the toolbars
- You also get a link to Mastodon, and Soundcloud, as well ad Dtube, so you have alternatives for social media, youtube, and music
- No Snap or Flatpak installed: They're really not pushing you towards installing native apps, they'd rather you use webapps
- Curiously, it lacks any way to create your own webapp out of a website: Firefox doesn't support that out of the box, and although you can enable site-specific browsers in the about:config page, it's not enabled by default
- For now, your only way to install new apps is through the web store, and you have no way of just creating your own, which seems like a big omission for Ubuntu Web remix.

## The web Store
- It's a first implementation
- Look and feel wise, it's still super simple
- There is virtually nothing in there for now, apart from a few social networks like Facebook, YouTube, or Instagram
- You can download these webapps, and you get a file, that you can install by double clicking it in the file manager, after you make it executable. Not very simple.
- You can also use the installer and go fetch the file from there.
- There is a wapp format that the developer created, that lets people package their own webapps, and submit them to the store through the project's gitlab page, but for now, nothing seems to have been added

## Anbox and Android apps
- Ubuntu web remix uses Anbox to allow running Android apps
- It ships with a few android apps preinstalled, including the default calculator, calendar, clock, contacts, email, files, gallery, music, and settings from Android
- You have the F Droid store by default, and you can sideload APK with an adb command line, although once again, an installer would be nice, since F-Droid won't have every Android app you might want
- Uses a pretty old and insecure version of Android by default, so it's not a perfect solution
- It doesn't seem to have many limits, as you could even install the Google Play Store, though it wouldn't allow me to connect at all, I think it might need Google Play Services support


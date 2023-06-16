# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## The Ultimate DEGOOGLED ANDROID ROM, now even BETTER!
 - [https://www.youtube.com/watch?v=m_fijLQxZLU](https://www.youtube.com/watch?v=m_fijLQxZLU)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-04-28 00:00:00+00:00

Download Safing's Portmaster for FREE and take control of your network traffic: https://safing.io/portmaster


I already talked about the /e/ Android ROM, a while ago, and while I really love this ultimate de-googled version of Android, there were also a few concerns about security, look and feel, how degoogled it all really is, and where the data is going. The /e/ project has also been updated quite a lot since my last video, so I think it's time to take another look at /e/.

Become a channel member to get access to a weekly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on ODYSEE: https://odysee.com/@TheLinuxExperiment:e
Or join ODYSEE: https://odysee.com/$/invite/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment


List of stuff /e/ removes from AOSP:
https://e.foundation/wp-content/uploads/2020/09/e-state-of-degooglisation.pdf

## Older Android version, looks and feels like older Android

Ok, so one of the main comments I got on the video is that /e/ is based on an old version of Android. It was Android 8 in my previous video. Of course, /e/ also has releases based on newer Android versions.
On my Galaxy S9+, it goes up to Android Q (Android 10), which is also the case for a lot of phones out there.

## Looks dated

One of my main problems with /e/ was that all the apps looked disjointed, using different accent colors, and sharing a kit-kat era look and feel.

I can happily report that with versions 0.15 and 0.16, this is no longer the case. The default apps, which are forks of open source android apps, now sport a nice white and blue color scheme, except for the email client and the maps app, which haven't been updated yet. 

## You're just giving your data to someone else

Another common comment I got on the previous video was that you were just giving your data to the /e/ project instead of giving it to Google.

While that, in itself, is a weird argument, as /e/ is a small nonprofit, and would really struggle to do anything with that data, it also doesn't apply here at all.

First, the account isn't mandatory: you can skip if if you'd prefer to use what you already have.

Second, the data you send to your /e/ account is encrypted, the /e/ project can't access it.

And third, /e/ doesn't sell ads, so they wouldn't even have any use for your data in the first place.

Now, speaking of the /e/ account, they only offered 1Gb of free storage, which was a meager amount, and you couldn't really upgrade that.

They now announced that, while the free tier is still only 1Gb, you can up that to 20Gb for 2 euros per month, all the way up to 1Tb for 13 euros per month. It's pricier than what the "big tech" companies offer, but it's still not a terrible deal, especially as this data isn't shared or accessed. If I didn't already have my own Nextcloud server, that's definitely something I'd be interested in, even if I didn't use /e/ on my phone.

The only issue is that this ecloud is basically access to a Nextcloud account, but you don't get to install your own apps on it

## Not completely degoogled, or as de-googled as Lineage OS

Now another common comment I got was "just use Lineage OS instead". While /e/ is a fork of Lineage, it's also going a lot further to remove Google stuff from AOSP.

Lineage still uses the Google DNS servers, so they know what your device is trying to access, and they also use Google to connect to captive portals, like airport wifi.
It also uses Google services to aid GPS positioning, and as the Android Open Source Project webview, which calls to Google as well.

/e/ removes the connectivity check to Google, replacing it with their own servers, they removed calls to the Google time servers and replaced them with the standard provider for internet time, and while the DNS servers aren't changed automatically, you can change them in the settings as well.

So, in short, Lienage OS is great, but if you want to remove every bit of Google from your phone, /e/ is a better option.

Now some people were also saying that /e/ has "stolen" code from Lineage OS and other apps, without giving credit. This has been proven to be completely false, as they are clearly stating what they based their stuff on in their FAQ:
https://e.foundation/get-started/

## Other concerns

Smartphones preinstalled with /e/ weren't available in the US or Canada when I made my previous video, now they are.

Some concerns were raised about security, especially since /e/ doesn't use the Play store, so how could we be sure that apps were unaltered binaries? the /e/ store uses the CleanAPK repositories.


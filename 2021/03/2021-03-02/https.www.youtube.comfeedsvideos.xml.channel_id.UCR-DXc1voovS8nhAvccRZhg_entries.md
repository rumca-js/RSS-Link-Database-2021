# Source:Jeff Gerling, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg, language:en-US

## 16 Drives, 1 Pi
 - [https://www.youtube.com/watch?v=afnszOuWt74](https://www.youtube.com/watch?v=afnszOuWt74)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg
 - date published: 2021-03-03 00:00:00+00:00

Let's see if I can get 16 janky old hard drives connected to 1 Raspberry Pi and make a giant RAID volume.

Well, not that giant, because these are janky old drives and none of them are more than 300 GB.

I'll be using the Broadcom MegaRAID card featured in my 'Hardware RAID on Raspberry Pi' video: https://www.youtube.com/watch?v=Zpfq8ZC2hyI

Here are affiliate links to the incredible (and incredibly *cheap*) drives I'm using in this video:

  - Kingston A400 SATA SSD (x4): https://amzn.to/3bN8S6Y
  - HP Proliant 300GB 10K 6 Gbps SAS HDD (x4): https://amzn.to/3dLmtOW
  - WD Green 500GB 5400rpm SATA HDD (x4): https://amzn.to/3gd0qzQ
  - Fujitsu Enterprise 73.5GB 3 Gbps SAS HDD (x4): https://amzn.to/3bJxUUz

Thanks again to Broadcom for sending me the MegaRAID card and storage enclosure!

Here's how I made the task list overlay: https://github.com/geerlingguy/obs-task-list-overlay

Support me on Patreon: https://www.patreon.com/geerlingguy
Sponsor me on GitHub: https://github.com/sponsors/geerlingguy

Contents: 

00:42 - Livestream Start
06:59 - Wiring up drives (data)
15:24 - Wiring up drives (power)
23:15 - Turning everything on
27:23 - Verifying drives are seen
50:53 - Creating 12-drive volume
1:12:29 - Questions & answers

#RaspberryPi #RAID #16Drives1Pi

## How to format a hard drive (with a sledgehammer)
 - [https://www.youtube.com/watch?v=HIAzknCJpL8](https://www.youtube.com/watch?v=HIAzknCJpL8)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg
 - date published: 2021-03-03 00:00:00+00:00

I asked Red Shirt Jeff to repair one of the SAS drives that was not spinning up. This is what he did.

Special thanks to the 'overkillbros', Thomas and Joe, from Germany, who sent me this drive (and four more that still worked :).

Support me on Patreon: https://www.patreon.com/geerlingguy
Sponsor me on GitHub: https://github.com/sponsors/geerlingguy

#SAS #RedShirtJeff #PercussiveMaintenance

## Hacking my PSU and more on the Universal Backplane
 - [https://www.youtube.com/watch?v=ncMyfV2XPTY](https://www.youtube.com/watch?v=ncMyfV2XPTY)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg
 - date published: 2021-03-02 00:00:00+00:00

After the last video, I figured I should clarify what I was trying to do with my PSU that led to me almost getting electrocuted.

Also, a lot of people were asking about the hard drive backplane I used, so I gave a few more details about the SFF-TA-1005 'Universal Backplane' reference that Broadcom sent me.

It's not commercially available, though the actual hardware unit was built from a SerialCables.com unit that is no longer available. They do have a newer version available, but it does not yet support 'tri-mode'. Only a few servers currently support all three of the SATA/SAS/NVMe protocols via one connector (assuming you use an adequate HBA like the MegaRAID I used in my last video).

See the previous video here: https://www.youtube.com/watch?v=Zpfq8ZC2hyI

Support me on Patreon: https://www.patreon.com/geerlingguy
Sponsor me on GitHub: https://github.com/sponsors/geerlingguy

#PSU #SAS

Contents:

00:00 - PS_ON to GND
02:26 - How it's supposed to work
04:05 - SFF-TA-1005 Tri-mode Backplane


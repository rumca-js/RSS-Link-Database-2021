# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## This thing runs OFFICE and ADOBE APPS like they were NATIVE?
 - [https://www.youtube.com/watch?v=fzzf2QnyPgY](https://www.youtube.com/watch?v=fzzf2QnyPgY)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-06-04 00:00:00+00:00

Visit https://www.linode.com/linuxexperiment for a 100$ credit on your new Linode account!

There are plenty of use cases where people might need access to some specific windows apps, and running some of them on Linux can be a hassle. Wine has come a long way, but it still fails to run some of the most popular apps without a huge performance hit, like MS Office, or the Adobe Suite. Fortunately, there might be a solution to run these apps as if they were native to Linux.

Become a channel member to get access to a weekly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on ODYSEE: https://odysee.com/@TheLinuxExperiment:e
Or join ODYSEE: https://odysee.com/$/invite/@TheLinuxExperiment:e


The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

## The Setup

Set up the KVM machine: https://github.com/Fmstrat/winapps/blob/main/docs/KVM.md
Set up Winapps: https://github.com/Fmstrat/winapps


Run this to start libvirt: sudo systemctl start libvirtd
Run this if the "default network" doesn't work for libvirt: sudo virsh net-start default
Add this to the ~/.local/bin/winapps script : export LIBVIRT_DEFAULT_URI=qemu:///system



Winapps is a script that will let you access windows applications, running on a windows virtual machine, right from your Linux desktop. It integrates a number of applications in your menu, so you can launch them like any native linux app, and they'll show up as "regular" Linux applications, in their own window, you won't need to use them in the VM's dedicated window.

I left the links to the install guides in the description below, they're going to be way more detailed than what I could fit in a 10 minute video.

My goal here is to try this out, see how well that works, and see if it's a viable alternative to other solutions, like dual booting.

Still, just to sum up the steps, you have to create a KVM virtual machine using Virt Manager, edit a few parameters of the VM, add to it a second disk drive for the necessary drivers, install Windows 10 PRO on it, and then create a user account, install required drivers, add some registry entries through a file, rename the computer and enable RDP, and then install the apps you want to use inside of that VM.

Then, you reboot the VM, and run a check to see if Winapps can connect to that virtual machine through that remote desktop protocol. Finally, you run the Winapps installer to detect the apps, and it will add them to your menu.

So, how does it run?
Well, it's really kinda nice. I only gave 2CPU threads to the VM, and 1GB of RAM, with the ability to go up to 4Gb, and still, every app started blazingly fast.

By default, Winapps only autodetects a handful of applications, including the whole Adobe Creative Cloud suite, the whole MS office suite.

In use, the apps showed up in my dock, I could resize the windows, move them around, minimize them, and interact with them as if they were native, although they don't use your window manager to display their window borders.

I could also copy paste text from my Linux desktop to the windows apps themselves. Winapps also seems to bind these applications to the right file types, so you can open a spreadsheet using Excel through Winapps, and it will work just fine, and you'll be able to save it in place, without any issues.

I tried running Word, Excel, and powerpoint, which all worked great. All features are accessible, the interface is snappy and responsive, it just works exactly as it would in windows.

I had to remove a small argument in the start command for outlook to work, but after that it launched and operated as intended, with a weird tendency to maximize itself even when I told it not to.

I also installed adobe Creative cloud, with more mixed results.
Photoshop opened after a really long loading time, and it took even more time displaying anything and letting me create a new document. After that, it worked alright, although there was a noticeable delay when using a brush to draw my masterpiece on the screen.

I'm pretty sure more advanced uses of this app, if they exist, will meet with a bit more friction and delays, but it's definitely usable once it's started.

InDesign flat out refused to work, launching with a weird overlay on top of it, and never responding to any action I tried.

Illustrator worked fine, I could open a blank template and play around with my incredible Illustrator skills. The "New documetn" window though, was trying to escape from my screen and not displaying anything apart from a cryptic title.

In general, for the Adobe CC suite, it's a bit hit or miss


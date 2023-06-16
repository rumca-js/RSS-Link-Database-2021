# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Run macOS on Linux with 1 COMMAND
 - [https://www.youtube.com/watch?v=6WgjQpm9VWE](https://www.youtube.com/watch?v=6WgjQpm9VWE)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2021-05-12 00:00:00+00:00

Get your free proof of concept for TuxCare: https://www.tuxcare.com

Most of you probably know that you can only run macOS on hardware that Apple sells, at least if you're not willing to go the hackintosh route, which can be painful and complex. Still, some of us might want, or need to test stuff out on Apple's operating system, fortunately, there is now a simple solution to do just that, with just one command line.

Become a channel member to get access to a weekly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on ODYSEE: https://odysee.com/@TheLinuxExperiment:e
Or join ODYSEE: https://odysee.com/$/invite/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment


Link to SOSUMI: https://snapcraft.io/install/sosumi/ubuntu
How to install snap: https://snapcraft.io/docs/installing-snapd
Mac OS Simple KVM: https://github.com/foxlet/macOS-Simple-KVM

Sosumi is a SNAP package that lets you install a Qemu virtual machine running Mac OS Catalina. It's nothing you couldn't do on your own with a bit more time, but this snap package has the advantage of being just one command line away, and taking care of all the setup for you.

Now be warned that Apple's End User Licence Agreement doesn't allow to run Mac OS in a VM on hardware that isn't made by Apple, so do this at your own risk!

As always with virtual machines, you need to ensure that your CPU supports virtualization in the BIOS. 

Once you're all set, you just open a terminal window, and run this command:

sudo snap install sosumi

Let the installation run its course, and you should get a menu entry called, you guessed it, SOSUMI.

Run that to initialize the VM. You should get a terminal window which shows you the download progress for the system image that will let you install macOS.

Click inside the window to focus is, and then press enter to start the installer.
After a while, you should end up in the installer window for Mac OS.

To begin with, you'll have to format the virtual disk that the VM has created for you. Double click on "disk utility", and select the disk called "Apple Inc. VirtIO Block media", with a size of 68Gb.

Then, click on "Erase", and select the format you'd prefer using, I used APFS, as that's the most recent Apple Filesystem, but it will work fine if you use Mac OS Extended.
Click the "Erase" button.

The operation should be pretty fast, and you can then close the disk utility window, and start the installer by double clicking on "Reinstall macOS".

Once the installation is complete, your VM will reboot and let you complete the first-run setup. You'll end up in Clover again. 
One last reboot, and you'll be able to select the "Boot mac OS frm Mac HD" option in Clover, the last option on the right.

Once the boot process is complete, you'll have to sift through a few settings screen, and log in using an Apple ID, or create one if you don't already have one.

Close the VM by shutting it down, and open your file manager. Snaps create a folder in your /home directory, to store everything, so head over there, and go to Sosumi, then Common.

Here, you'll find a file called "launch". 
First, make a copy, in case something goes wrong, so you can restore the previous version, open the file with your text editor of choice.

In this file, you'll see all the parameters for the Qemu virtual machine.

-m defines the memory usage of the VM, in gigabytes. By default, it's 2, but as I have 32Gb on my device, I'll put 16 in there.

Now, for the window resolution, it's a bit more involved.

Type diskutil list

Grab the identifier for the disk that reads EFI,  it should be the same as mine, disk2s1.

Then type
sudo diskutil mount disk2s1

or replace disk2s1 by the correct identifier for your EFI disk.

Now open the Finder, and go to the EFI disk in the sidebar. Open the CLOVER folder, and ediut the config.plist file, using textedit.

Here, you'll find a line that reads screenresolution. Change the default of 1280x720 by what you want to use, in my case, 1920x1080. Save the file.

Now, shut down the VM, and restart it.
Right when you see the terminal window open, hit "escape". You'll see an interface that looks like a BIOS. Select device manager, OVMF Platform Configuration and then "change preferred".

Press the F10 key to save, and then escape until you get back to the main menu, where you'll then select "Continue".

You can also change the CPU core count affected to the VM. By default, you'll get 4 threads for 2 cores, listed in the line "-smp 4,cores=2".
You can change that by putting another number.


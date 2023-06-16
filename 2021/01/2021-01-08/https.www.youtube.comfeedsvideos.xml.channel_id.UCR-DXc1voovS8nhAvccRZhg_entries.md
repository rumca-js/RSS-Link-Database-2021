# Source:Jeff Gerling, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg, language:en-US

## I lied... WiFi 6 on the Raspberry Pi is NOT faster than Ethernet
 - [https://www.youtube.com/watch?v=1kWAdtoq8TQ](https://www.youtube.com/watch?v=1kWAdtoq8TQ)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg
 - date published: 2021-01-08 00:00:00+00:00

As it turns out, my benchmarking process was flawed, and I had to learn a bit about the Linux networking stack to figure out why!

Special thanks to commenter marvell marvell for pointing out the obvious, and to Javier Choclin for suggesting I try out the MZHOU adapter, which led me down this path towards enlightenment.

Support me on Patreon: https://www.patreon.com/geerlingguy
Sponsor me on GitHub: https://github.com/sponsors/geerlingguy

Products in this video (affiliate links):

  - MZHOU M.2 WiFi/Bluetooth to PCIe Adapter: https://amzn.to/34A3sth
  - ASUS 10G PCIe Ethernet Adapter: https://amzn.to/38wYOiL
  - Intel WiFi 6 AX200 Desktop Kit: https://amzn.to/38p3E0V
  - EDUP WiFi 6 PCIe Card: https://amzn.to/3pnFF8S
  - Intel I340-T4 4-port 1 Gbps Ethernet card: https://amzn.to/37vHQR6

Referenced in this video:

  - Raspberry Pi PCI Express Card Database: https://pipci.jeffgeerling.com
  - Hannes' Stack Exchange answer: https://superuser.com/a/1553310/80658
  - wpa_supplicant hook in dhcpcd source: https://github.com/rsmarples/dhcpcd/blob/master/hooks/10-wpa_supplicant

#RaspberryPi #ComputeModule4 #WiFi6

Contents:

00:00 - I was wrong!
01:27 - Laying out the facts
02:41 - Yay, MZHOU adapter works!
03:13 - iperf3 is weird on Linux
04:19 - Working around the problem
04:49 - Revised benchmarks
05:50 - What about wpa_supplicant?
06:33 - Use the source, Jeff!
07:48 - More exploration
08:18 - End + Bloopers


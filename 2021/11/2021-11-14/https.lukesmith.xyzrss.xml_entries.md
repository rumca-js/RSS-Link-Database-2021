# Source:Luke Smith, URL:https://lukesmith.xyz/rss.xml, language:en-US

## Important notes for LARBS users
 - [https://lukesmith.xyz/updates/important-notes-for-larbs-users/](https://lukesmith.xyz/updates/important-notes-for-larbs-users/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2021-11-14 00:00:00+00:00

<p>Two notes for <a href="https://larbs.xyz">LARBS</a> users:</p>
<ol>
<li>Xorg went through some updates last week that changed how it
calculates dots-per-inch (DPI) on screens. There's a chance that
you might update and find your font extra large or small. If so, you
can just manually add <code>xrandr --dpi 96</code> to the beginning of your
<code>xprofile</code> to set the DPI to the typical 96 (or whatever number
looks best).</li>
<li>I have no switched new installs of LARBS from using Pulseaudio to
Pipewire as an audio backend, although it will also come with
<code>pipewire-pulse</code> to maintain compatibility with Pulseaudio programs.
If you would like to update the dotfiles, remember to install the
<code>pipewire</code> and <code>pipewire-pulse</code> packages. There should be no major
difference in user experience, although using Pipewire will avoid
some silly Pulseaudio bugs.</li>
</ol>


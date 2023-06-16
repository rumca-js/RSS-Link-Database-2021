# Source:Louis Rossman, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCl2mFZoRqjw_ELax4Yisf6w, language:en-US

## Test of GoPro 360 VR camera on a bike in NYC while Louis Rossmann rants & raves into the abyss.
 - [https://www.youtube.com/watch?v=2IKBfvtWXMw](https://www.youtube.com/watch?v=2IKBfvtWXMw)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCl2mFZoRqjw_ELax4Yisf6w
 - date published: 2021-03-28 00:00:00+00:00

https://tinyurl.com/rossmatrix
Let's get Right to Repair passed! https://gofund.me/1cba2545
GoPro 360 camera: http://bit.ly/gopro360max

IMO, isn't even ready for primetime  Feel free to call me an idiot if I am missing something shockingly simple.. but honestly, even if I am missing something it, begs the question as to whether this *should* be this hard to get right out of the box as a basic consumer product. 

This video was helpful https://youtu.be/xlOhluai5mk as well as this tool: https://github.com/google/spatial-media/releases

1) The gopro player software has edit features. However, you cannot drag & drop, or append via menu, additional files to a session. So it won't let me combine multiple files. Other people have asked, you literally have to upload the files to the cloud for it to combine it into one video it can then re-download.. which is subscription based. This means you need to run the video through a video editor, which will require you to re-render the video(as opposed to a tool like avidemux, where you just add the files one after the other into one file without re-rendering which is a gigantic waste of CPU)

2) sony vegas can import files directly from the camera, but it cannot import files after they go through the gopro player export feature which I think you're supposed to do so you can work with them(the files straight from the camera show up on youtube like this https://www.youtube.com/watch?v=lR1foUl3Emc - totally unusable) 

3) If you import the files into vegas directly from the camera, you can edit, and even look around in the preview window. However, every single render option it gives you produces a video file that VLC, MPC-HC, and youtube itself cannot process or use. See here: this has been processing for almost a day... dead.  https://youtu.be/ENbSZHTwnvo  The file doesn't play in anything here either. To be clear, 360 was selected in the session properties prior to beginning. 

4) Vegas cannot open HEVC or cineform files that are shot out of the gopro player software, which is what you use to turn the files from the camera into something youtube can understand as 360 video(see here - this is what the files look like coming out of the gopro player tool  https://youtu.be/17DSGd1Xuio  )

5) resolve studio can see the files after the gopro player app has decoded them, but they look like what you see above when you render unless you run it through some other tool to inject 360 metadeta for youtube here https://github.com/google/spatial-media/releases

6) davinci resolve studio cannot import the files directly as they are from the camera. Vegas CAN import directly from the camera, but what it renders out using ANY SETTING THAT IS COMPATIBLE WITH A 360 SESSION is blackscreen video. 

7) avidemux sees the 360 files as a warped mess with behind you on the left, behind you on the right, and in front of you in the center that looks even worse than this.

8) I bought separate protective lens covers from gopro for the camera for $20, they show up with giant gashes on them. Weak. So did the ones in the box! The ones in the box, fine - it's a refurb camera, but why the new ones too?

TL;DR - I wasted about three hours on this so you don't have to. GIVE ME A TOOL TO COMBINE THE 360 FILES INTO ONE! Most cameras like this do not record to one file - they record to multiple files after they hit 4 GB, so even if you have one 30 minute video, it may be split into 5-8 files depending on the bitrate of the recording. The fact that they give you a tool that can output files, but not mux them together is horrific, and what I've come to expect from a company that releases software that takes over 20 minutes to pair a phone to a camera. See here: https://www.youtube.com/watch?v=KPTq_obf-m4

I find locating PM_SLP_S4_L on an 820-3115 with no corrosion easier than getting this to work as intended. If you want 3D video files you can look at and playback in their software, one clip at a time, this is a lovely device. If you want files you can use the 360 feature with on youtube, or edit, you'll probably spend hours googling and screwing with stuff the way I did and want to pull your hair out. 

Also, you can't just download an EXE because that would make life easy, you can only get it through the microsoft app store so if you removed that from your windows install, enjoy reinstalling the microsoft app store just for this.


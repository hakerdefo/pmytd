# pmytd
pmytd (Poor Man's Youtube Downloader) is a simple bash front end to youtube-dl.

pmytd can,

  - Download videos from youtube and other video sharing websites.
  - Download and extract audio (mp3) from videos on youtube and other video sharing websites.
  - Download entire youtube playlists (video and audio).

pmytd is a helper script for Ricardo Garcia's wonderful youtube-dl.
You can view the list of all websites from which pmytd can download video(s) here,

[pmytd supported websites]


### pmytd Dependencies :

pmytd needs to have following applications installed in order to function,

* [youtube-dl] - Small command-line program to download videos from YouTube.com and other video sharing websites. youtube-dl is available in repos of some distributions but available version most likely would be severly outdated. Here is the right way to install it. Open terminal and run following commands,
```sh
$ sudo wget https://yt-dl.org/downloads/latest/youtube-dl -O /usr/local/bin/youtube-dl
```
```sh
$ sudo chmod a+x /usr/local/bin/youtube-dl
```
* [python] - Python is a widely used general-purpose, high-level programming language. Python should most likely be installed by default on most linux distributions. If it is not installed please use your distro's package manager and install it.
* [FFmpeg] - A complete, cross-platform solution to record, convert and stream audio and video. Again ffmpeg should already be installed by default on most distros. If not install it via your distro's package manager. In some distros it is called avconv. ffprobe or avprobe are also required.
* Downloads Directory - pmytd is hard-wired to download video and audio to the Downloads directory under user's home directory. Downloads directory should already be there by default but just in case make sure you have Downloads directory under your home folder.


### Installation :

Download [pmytd-master] zip, extract it's contents and copy 'pmytd' file to '/usr/local/bin/' directory,
```sh
$ sudo cp pmytd /usr/local/bin/
```
Next make it executable,
```sh
$ sudo chmod a+x /usr/local/bin/pmytd
```


### Usage :

Open terminal, run pmytd, feed it a video link, enjoy.


### Update :

Youtube and other video sharing sites continually change their APIs. So it is advised to keep youtube-dl updated to latest version. You can check for youtube-dl updates via 'Check for updates' option in pmytd menu. If there is a newer version available then you can update youtube-dl by running following command in terminal,
```sh
$ sudo youtube-dl -U
```


### License :

[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">pmytd</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/pmytd)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.


[pmytd supported websites]:http://rg3.github.io/youtube-dl/supportedsites.html
[youtube-dl]:http://rg3.github.io/youtube-dl/
[python]:https://www.python.org
[FFmpeg]:https://ffmpeg.org/
[pmytd-master]:https://github.com/hakerdefo/pmytd/archive/master.zip

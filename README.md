# pmytd
pmytd (Poor Man's Youtube Downloader) is a simple bash front end to youtube-dl.

pmytd can,

  - Download videos from YouTube and other video sharing websites.
  - Download and extract audio (MP3) from videos on YouTube and other video sharing websites.
  - Download entire YouTube playlists (video and audio).

pmytd is a helper script for Ricardo Garcia's wonderful youtube-dl.
You can view the list of all websites from which pmytd can download video(s) here,

[pmytd supported websites]


### pmytd Dependencies :

pmytd needs to have following applications installed in order to function,

* [youtube-dl] - Small command-line program to download videos from YouTube and other video sharing websites. youtube-dl is available in repos of some distributions but available version most likely would be severly outdated. If you have installed youtube-dl using your package manager, please update it via the "Check for updates" option in pmytd menu. pmytd will help you install the current version of youtube-dl if it's not installed on your system.
* [Python] - Python is a widely used general-purpose, high-level programming language. Python should most likely be installed by default on most linux distributions. If it is not installed please use your distribution's package manager and install it.
* [Wget] - GNU Wget can be used for retrieving files using HTTP, HTTPS and FTP, the most widely-used Internet protocols. It is a non-interactive commandline tool, so it may easily be called from scripts, cron jobs, terminals without X-Windows support, etc. Wget can be installed using your distribution's package manager.
* [cURL] - cURL is a command line tool and library for transferring data with URL syntax. cURL is available in repositories of almost every Linux distribution so you can install curl easily via your package manager.
* [FFmpeg] or [Libav] - You will need either FFmpeg or Libav only if you want to use pmytd to extract audio (MP3) from videos. FFmpeg is a complete, cross-platform solution to record, convert and stream audio and video. FFmpeg should already be installed by default on some distributions. If not install it via your distribution's package manager. Libav provides cross-platform tools and libraries to convert, manipulate and stream a wide range of multimedia formats and protocols. If you want to use Libav with pmytd, please install package "libav-tools" using your distribution's package manager.


### Installation :

Download [pmytd-master] zip, extract its contents and copy "pmytd" file to "/usr/local/bin/" directory,
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

YouTube and other video sharing sites continually change their APIs. So it is advised to keep youtube-dl updated to latest version. You can easily update youtube-dl via "Check for updates" option in pmytd menu.


### License :

[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">pmytd</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/pmytd)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.

[pmytd supported websites]:http://rg3.github.io/youtube-dl/supportedsites.html
[youtube-dl]:http://rg3.github.io/youtube-dl/
[Python]:https://www.python.org
[Wget]:https://www.gnu.org/software/wget/
[cURL]:http://curl.haxx.se
[FFmpeg]:https://ffmpeg.org/
[Libav]:https://libav.org/
[pmytd-master]:https://github.com/hakerdefo/pmytd/archive/master.zip

# pmytd
pmytd (Poor Man's Youtube Downloader) is a simple bash front end to youtube-dl.

pmytd can,

  - Download videos from YouTube in 4K and 1080P.
  - Download and extract HQ audio (320 kbps MP3) from YouTube videos.
  - Download entire YouTube video playlists in 4K and 1080P.
  - Download and extract HQ audio (320 kbps MP3) from YouTube playlists.
  - Install youtube-dl if it's not available.
  - Update youtube-dl to the latest version.


### pmytd Dependencies :

pmytd needs to have following applications installed in order to function,

* [youtube-dl] - Small command-line program to download videos from YouTube and other video sharing websites. youtube-dl is available in repos of some distributions but available version most likely would be severly outdated. If you have installed youtube-dl using your package manager, please update it via the "Check for updates" option in pmytd menu. pmytd will help you install the current version of youtube-dl if it's not installed on your system.
* [Wget] - GNU Wget can be used for retrieving files using HTTP, HTTPS and FTP, the most widely-used Internet protocols. It is a non-interactive commandline tool, so it may easily be called from scripts, cron jobs, terminals without X-Windows support, etc. Wget can be installed using your distribution's package manager.
* [FFmpeg] or [Libav] (Optional) - You will need either FFmpeg or Libav if you want to download videos in 4K or 1080P resolutions or if you wish to extract audio (MP3) from videos. If you want to download videos in 720P or lower resolutions and don't need to extract audio as MP3 you won't need FFmpeg-Libav. FFmpeg is a complete, cross-platform solution to record, convert and stream audio and video. FFmpeg should already be installed by default on some distributions. If not install it via your distribution's package manager. Libav provides cross-platform tools and libraries to convert, manipulate and stream a wide range of multimedia formats and protocols. If you want to use Libav with pmytd, please install package "libav-tools" using your distribution's package manager.


### Installation :

Download [pmytd-master] zip, extract its contents and copy **pmytd** file to **/usr/local/bin/** directory,
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


### Support :

If you like **pmytd**, please consider supporting it, even the smallest contribution goes a long way. It is quick & easy via PayPal, Buy Me a Coffee or Liberapay:  

[![Support via PayPal](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://paypal.me/hakerdefo)  
[!["Buy Me A Coffee"](https://user-images.githubusercontent.com/1376749/120938564-50c59780-c6e1-11eb-814f-22a0399623c5.png)](https://www.buymeacoffee.com/hakerdefo)  
[![Support via Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/hakerdefo/donate)  


### License :

[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">pmytd</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/pmytd)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.

[youtube-dl]:http://rg3.github.io/youtube-dl/
[Wget]:https://www.gnu.org/software/wget/
[FFmpeg]:https://ffmpeg.org/
[Libav]:https://libav.org/
[pmytd-master]:https://github.com/hakerdefo/pmytd/archive/master.zip

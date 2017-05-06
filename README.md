# yle2m4v

v1.2

Download video file (with subtitles, if any) from Yle Areena and
convert the downloaded FLV file into a M4V file. The FLV file is
inserted as-is into the M4V container; there is no demuxing/remuxing
involved, so video quality is not changed.



Usage: yle2m4v [url]

url - Yle Areena page for video file

The following external binaries have to be available in path:
- zsh
  - this is a zsh script
  - zsh is assumed to be in /usr/bin/zsh, OSX has it in /bin/zsh,
    edit as appropriate     
- yle-dl
  - for downloading, see http://aajanki.github.io/yle-dl/
- either AdobeHDS.php or youtube-dl, see yle-dl documentation
- ffmpeg
  - for converting, see http://www.ffmpeg.org/
    (probably available via your system's package manager)

(c) 2015-2017 Ola Rinta-Koski

## TODO
- add -f (force) option to clobber existing FLV file
- this script's functionality should really be part of yle-dl, so consider
   this a quick stopgap hack

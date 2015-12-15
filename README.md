# yle2m4v
Download video file (with subtitles, if any) from Yle Areena
and convert the downloaded FLV file into a M4V file

Usage: yle2m4v [url]

url - Yle Areena page for video file

The following external binaries have to be available in path:
zsh    - this is a zsh script
       - zsh is assumed to be in /usr/bin/zsh, OSX has it in /bin/zsh,
         edit as appropriate     
yle-dl - for downloading
         http://aajanki.github.io/yle-dl/
ffmpeg - for converting
         http://www.ffmpeg.org/
         (probably available via your system's package manager)

 (c) 2015 Ola Rinta-Koski

## TODO
- handle multiple subtitle languages (for now, none or 1 language assumed)
- what to do if FLV/SUB/M4V file exists? clobber (like now), or not?
- this functionality should really be part of yle-dl, so consider
   this a quick stopgap hack

Spotify-Downloader [![Gittip](http://badgr.co/gittip/fgribreau.png)](https://www.gittip.com/fgribreau/)
==================

A proof-of-concept that transforms a Spotify playlist to a direct-download list.

**I accept pull requests**. If someone would like to add a web-interface to Spotify-downloader
I'll be more than happy to accept the merge.

Usage
-----

* `npm install spotify-downloader`
* Drap & drop tracks from Spotify into a text file (e.g. playlist.txt )
* Edit `./bin/spotify-downloader` and replace the `key`'s value by your own [FilesTube API key](http://www.filestube.com/api.html)
* Run `cat playlist.txt | ./bin/spotify-downloader`
* Done.


Disclaimer
----------

* It's a simpley mashup, Spotify-downloader does nothing else that making a bridge between the Spotify Web API and FilesTube API.
* Please don't download content that you don't have a legal right to.
* If you believe I'm infringing your intellectual property somehow, please send me a proper DMCA Notice to abuse[***_at_***]fgribreau.com

Licence
-------

              DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                        Version 2, December 2004

     Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

     Everyone is permitted to copy and distribute verbatim or modified
     copies of this license document, and changing it is allowed as long
     as the name is changed.

                DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
       TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

      0. You just DO WHAT THE FUCK YOU WANT TO.

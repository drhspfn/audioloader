# AudioLoader | release 0.5
## Short Description
Console audio search/download application
[screenshots](https://imgur.com/a/frMazQv)

In the screenshots there is no `SoundCloud` item. I may update the screenshots in the future

## More details
* `YouTube Music`, `YouTube`, `Deezer` and `SoundCloud` are now available to search. The list is available in the `Help` menu in the app
* In `Settings' there is an option:
  + Change the download path
  + Change `Deezer ARL` [instruction](https://www.dumpmedia.com/deezplus/deezer-arl.html)
  + Authorize for `YouTube Music`. In case the tracks are 18+ 
  + Unlink, or relink YouTube Music. If already tethered



After using one of the search types, you get to a menu with a list of results. When you select it, it will start downloading to a folder, by default the `DOWNLOADS` folder in the root directory

## In future
* ~~Add support for `SoundCloud`~~
* Update notification `(Done, waiting for release)`
* Adding covers when downloading from YouTube\YT Music. `(Done, waiting for release)`
* Deezer Synchronized Texts Download `(Done, waiting for release)`
* `Genius` and ~~`MusixMatch`~~ lyrics search (see P.S#3) `(Done, waiting for release)`
* A separate little app for downloading videos from `YouTube`. (Make it separate, or a menu in the main?...idk..)
* Fix, abrupt exits from the app. `(Done, waiting for release)`
* Possible support for platforms other than `Windows`
* It is possible to do Lyric video generation, or play audio, idk. (the second is unlikely.)
* Perhaps the optimization (see P.S#2)
* Maybe something else...

I don't plan to distribute the open sourse. There will be a build for Windows in the release.

~~The build contains the standard `config,json`~~(see P.S#1). ~~And also it is obligatory to have `ffmpeg.exe` in the root~~ (see P.S#4)



## Releases
__(Weight considering `ffmpeg.exe`)__
* One is an assembled program in one file, `ffmpeg.exe` and `config.json`. `(Weight ~204 mb)`
* The other, an application assembled in a folder. `(Weight ~293 mb)`



## P.S
1. Added standard config to the code.But on versions `pre0.3` and `release 0.5` you still need `config.json` in the root directory
2. Perhaps it would have been a release by now, but I'm not sure about the optimization
3. Genius API support.
4. The  release 1.0 `OneFile` will be compressed into a single file. After the first run, `config.json` will be created. The `OneDir release` is structurally unchanged

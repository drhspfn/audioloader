# AudioLoader | release 0.5
## Short Description
Console audio search/download application
[screenshots](https://imgur.com/a/frMazQv)

## More details
* `YouTube Music`, `YouTube`, and `Deezer` are now available to search. The list is available in the `Help` menu in the app
* In `Settings' there is an option:
  + Change the download path
  + Change `Deezer ARL` [instruction](https://www.dumpmedia.com/deezplus/deezer-arl.html)
  + Authorize for `YouTube Music`. In case the tracks are 18+ 
  + Unlink, or relink YouTube Music. If already tethered



After using one of the search types, you get to a menu with a list of results. When you select it, it will start downloading to a folder, by default the `DOWNLOADS` folder in the root directory

## In future
* ~~Add support for `SoundCloud`~~
* Possible support for platforms other than `Windows`
* Perhaps the optimization
* Maybe something else...

I don't plan to distribute the open sourse. There will be a build for Windows in the release.

The build contains the standard `config,json`. And also it is obligatory to have `ffmpeg.exe` in the root

## Releases
__(Weight considering `ffmpeg.exe`)__
* One is an assembled program in one file, `ffmpeg.exe` and `config.json`. `(Weight ~251 mb)`
* The other, an application assembled in a folder. `(Weight ~303 mb)`



p.s: Perhaps it would have been a release by now, but I'm not sure about the optimization

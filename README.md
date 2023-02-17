Helper script for [my own music app](https://blog.kurcreative.com/kur2302030906).

How to add musics
1. Run `./copy-music-structure` to copy directory structure 
   from `/storage/emulated/0/Music` to `.`
2. Add musics each directory manually(Categorizing)
3. Run `./rm-empty-dirs` to remove useless noises in new `./storage` dir
4. (CAREFUL!) Run `./UPDATE-MUSIC-APP` to below side-effect operation
    1. Copy new `./storage` dir to `/storage/emulated/0/Music`
    2. Append `tree-mpaths` result to `~/.config/cmus/playlists/0all.m3u8`

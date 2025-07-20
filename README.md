# zvu
a mpv music player tui frontend

depends on https://github.com/netkv/BufferMaker for now, i might integrate that in future

static version has buffermaker integrated, however i might forget to update it sometime, in this case just download it and run like any bash script

depends on mpv (the backend) and `shuf` command for shuffle

usage:

zvu playlist.m3u

zvu directory/

find | zvu (can accept any list of files separated by newlines)

this will load up list into current playlist, keybindings are indicated by left sidebar

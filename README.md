### Hey guys 👋, Thanks for checking out

ask a question?? [<kbd>Submit a New Issue</kbd>](https://github.com/gocs/gocs/issues/new)

🗺 I'm interested in maps (geography), \
🎮 game dev,\
🌐 multiplayer networking,\
🎛 electronic dance music,\
🎴 a little bit of anime,\
🎭 constructed languages,\
and especially ⚒ worldbuilding.\
🎨 I know how to use unity3d, ableton live, font forge, gimp, and blender.\
🎮 I occasionally play video games.\
👨‍💻 I would only use golang for my backend.

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="left" src="https://github-readme-stats.vercel.app/api?username=gocs&count_private=true&show_icons=true&theme=dark" />
</a>

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gocs&hide=html,asp,css&theme=dark" />
</a>

<br><br><br><br><br><br><br><br><br><br><br><br>

#### vtuber

🥟🌙🥐🔎<br>
👑🍹⚖<br>




#### how to make a `go.mod` file

The idiomatic rule for golang modules to be initialized is to have the repository location (i.e. URL) be the module name. The module is usually named `<repository host>/<user>/<repository name>` format. The naming format also reflects my current working directory as `~/Desktop/github.com/gocs/<repository name>` for example.

```sh
$ #             ↓ current directory
$ #             ↓    ↓ split the lines
$ #             ↓    ↓                ↓ get the last three lines
$ #             ↓    ↓                ↓          ↓ add `/` after every line
$ #             ↓    ↓                ↓          ↓                    ↓ merge all lines
$ #             ↓    ↓                ↓          ↓                    ↓             ↓ remove last char
$ go mod init $(pwd| sed 's/\//\n/g'| tail -n 3| sed -ne 's/$/\/&/p'| tr -d '\r\n'| sed s'/.$//')
```

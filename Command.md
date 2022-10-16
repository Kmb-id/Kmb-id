# code perintah install termux di android 5 or 6
```
$ cd ../usr/etc/apt
$ ls
$ echo "deb https://packages.termux.dev/termux-main-21/ stable main" > sources.list
$ cd sources.list.d
$ ls
$ echo "deb https://termux.dev/science-packages-21-bin science stable" > science.list
$ echo "deb https://termux.dev/game-packages-21-bin games stable" > game.list
$ cd ~
$ pkg update
$ apt upgrade
```

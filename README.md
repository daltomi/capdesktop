## deskshot.sh - Screenshot of virtual desktops

Take a screenshot of the selected desktops and merge them into a single image.


<img src="https://github.com/daltomi/deskshot/raw/master/screenshots/deskshot.png"/>


### Help

```
Syntax: deskshot.sh [options]
  Options:
  -h          help
  -jv         join vertical (default)
  -jh         join horizontal
  -d [num]    delay for each shot (default: 1 seg.)
  -s          capture stack/overlapped windows
  -p          capture mouse pointer
  -i [num]    desktops ids, start at 0 (default:-1 == all)
  -r [value]  resize the image, format WxH
  -l          print script log
  -v          print version and exit

Example:
  deskshot.sh              (capture all desktops)
  deskshot.sh -i "0 2 4"   (capture desktop 0,2 and 4)
  deskshot.sh -i 2         (capture only desktop 2)
  deskshot.sh -r 800x600   (resize to 800x600)
```

#### Dependencies:

Tools are detected at runtime.

A list of dependencies is indicated in the header of the script.

#### GPG key:

`gpg --keyserver gozer.rediris.es --recv-keys EA8BDDF776B54DD1`


#### AUR:

Package [deskshot.sh](https://aur.archlinux.org/packages/deskshot.sh)


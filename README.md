## capdesktop.sh - Screenshot of virtual desktops

### Dependencies:

```bash
 External tools:
     - scrot
     - xdotool
     - convert (ImageMagick)
 Base tools:
     - mktemp
     - whereis
     - grep
     - basename
     - echo
     - rm
```

### Help

```bash
Syntax: capdesktop.sh [options]"
  Options:
  -h          help
  -jv         join vertical (default)
  -jh         join horizontal
  -d [num]    delay (default: 1 seg.)
  -s          stack windows
  -p          capture mouse pointer
  -i [num]    desktops ids, start at 0 (default:-1 == all)
  -l          print script log

  Example:
   capdesktop.sh              (capture all desktops)
   capdesktop.sh -i "0 2 4"   (capture desktop 0,2 and 4)
   capdesktop.sh -i 2         (capture only desktop 2)
```

<img src="https://github.com/daltomi/capdesktop/raw/master/screenshots/capdesktop.png"/>


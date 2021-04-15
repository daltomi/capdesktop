## capdesktop.sh - Screenshot of virtual desktops

Take a screenshot of the selected desktops and merge them into a single image.

<img src="https://github.com/daltomi/capdesktop/raw/master/screenshots/capdesktop.png"/>


### Help

```bash
Syntax: capdesktop.sh [options]
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

Example:
  capdesktop.sh              (capture all desktops)
  capdesktop.sh -i "0 2 4"   (capture desktop 0,2 and 4)
  capdesktop.sh -i 2         (capture only desktop 2)
  capdesktop.sh -r 800x600   (resize to 800x600)
```

### Dependencies:

Please, read the header of the script.


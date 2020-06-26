 Font
-------
Die Font ist hier zu finden:

[github.com/theleagueof/blackout](https://github.com/theleagueof/blackout.git)

 Mögliche Installation:
----------

Simply copy all `*.ttf` or `*.otf` files to `~/.fonts/`.


*or install the font for all Users on your system:* 
```bash
# create font directory
sudo mkdir /usr/share/fonts/36c3
sudo chown $USER /usr/share/fonts/36c3
# copy font to direcotry
cp fonts/Blackout_*.ttf /usr/share/fonts/36c3/
# reload font cache
fc-cache
```

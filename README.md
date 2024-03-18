# ax206 LCD

A simple python script to write an image to a ax206 LCD using libusb. Works the same as https://github.com/amyeo/kipye-lcd

Tested on linux. Other platforms pending.

# Install dependencies

```
$ sudo pacman -S python-libusb1
```

# Usage example

This will require sudo to write to the device.

```
$ sudo python main.py  --image=nijika.png --set-backlight=5
$ sudo python main.py  --image=nijika.png
$ sudo python main.py  --set-backlight=5
```
This is intended for seeed-voicecard-2mic usage on OSMC

The file /boot/config.txt should contain right order as following:
[all]
...
dtoverlay=pisound
dtparam=audio=on
dtoverlay=i2s-mmap
dtparam=i2s=on
dtoverlay=seeed-2mic-voicecard

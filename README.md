# Locate-THM

In this room you will test your steganography, metadata and location skillset.

You can find the room [here](https://tryhackme.com/room/locate)

## Challenge 1

to extract the metadata i ran this command:
``` shell
$ exiftool Challenge1.png
ExifTool Version Number         : 13.55
File Name                       : Challenge1.png
Directory                       : .
File Size                       : 552 kB
File Modification Date/Time     : 2026:07:11 02:38:00-04:00
File Access Date/Time           : 2026:07:11 02:38:01-04:00
File Inode Change Date/Time     : 2026:07:11 02:38:00-04:00
File Permissions                : -rw-rw-r--
File Type                       : PNG
File Type Extension             : png
MIME Type                       : image/png
Image Width                     : 994
Image Height                    : 653
Bit Depth                       : 8
Color Type                      : RGB
Compression                     : Deflate/Inflate
Filter                          : Adaptive
Interlace                       : Noninterlaced
SRGB Rendering                  : Relative Colorimetric
Pixels Per Unit X               : 2835
Pixels Per Unit Y               : 2835
Pixel Units                     : meters
Author                          : THM{_______________}
Image Size                      : 994x653
Megapixels                      : 0.649
```
and we can see that the flag is in the author field

Next i went to yandex to do a reverse image search
<img src="yandex1.png"></img>

# Challenge 2

This challenge has no hidden flags and is purely a image location task.


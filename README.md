# Others
My small collection of different usefull scripts

## fotosort.py
Script will sort your photo arhive. New directory structure will be created:
```
<year>/<Month number><month name>/.<file extention>
```
Example:
d:\готово\2018\10 - October\\.mp4\29_20181028_153733.mp4

## video-encode.py
Will walk through dir and all subfolders and compress all video files found to HEVC (best codec corrently. HW decoding support by all modern phones and CPU). 
You can supress h.264 reencoding, if you like. H.264 is also good codec. Helps to compress old videos (like MOV or early MPEG) to save space. Some videous could be compressed without noticable quality drop 20x!
You should install ffmpeg first!

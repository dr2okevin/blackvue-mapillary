# BlackVue to Mapillary

This tool stitches video and gps files to a format that can be uploaded to mapillary.

Tested with
* BlackVue DR750S-2CH
* BlackVue DR650GW-2CH IR

put video files, and gps files (if not in video included) into to video folder. Run index php, you will get a all.mp4 and a all.gpx  
don't mix front and rear video.  
You can use the mapillary video upload to upload both files.  

Requirements
* php
* gpsbabel (path can be changed in Classes/Gpx.php)
* ffmpeg (path can be changed in Classes/Video.php)

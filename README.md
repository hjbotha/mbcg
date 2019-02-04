# moviebarcodegenerator

mbcg: A script to create movie barcodes from video files

Prerequisites: ffmpeg, mediainfo, bc, imagemagick

Usage: mbcg -f video file [-w height] [-w width] [-b first second] [-e last second] [-d]  
-f Video File  
-w Barcode Width (default is 1920)  
-h Barcode Height (default is 1080)  
-b Start of movie in seconds (after titles; default is 0)  
-e End of movie in seconds (before credits; default is runtime)  
-l Width of each line. Default: 1\
-d Do not delete original .png files during processing  
   Move to processed directory instead  
-i Resize barcode to this width after generation. Defaults to barcode width.  


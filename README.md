# Movie Barcode Generator

mbcg: A script to create movie barcodes from video files  
Usage: mbcg -f video file [-w height] [-w width] [-b first second] [-e last second] [-d]  
-f Video File  
-w Barcode Width (default is 1920)  
-h Barcode Height (default is 1080)  
-b Start of movie in seconds (after titles; default is 0)  
-e End of movie in seconds (before credits; default is runtime)  
-d Do not delete original .png files during processing  
     Move to processed directory instead  

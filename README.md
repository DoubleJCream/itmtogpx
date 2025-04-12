# ITM To GPX (Updated)

**[Download here](https://github.com/DoubleJCream/itmtogpx/releases)**

## Converts any *.itm file of GPS Photo Tagger to a *.gpx file.

With processing multiple files at the same time it makes exporting out of **GPS Photo Tagger** much easier. You can use the .gpx file for other programs supporting gpx.

Not supported are: Pictures. Only the gps data will be exported (If you use a gps tracker like Travel Honey etc)

## Attention
I wanted to convert some old Holux itm files, unfortunately the original project from Eusebius1920 wasn't working for me. As my first project I updated the code to .net framework 4.8 and the SharpZipLib to v1.4.2
I also switched the button language from German to English.
I really didn't look into the function of the code except to figure out why it wasn't working for me.

## Used Libraries: 
* "Simple C# Wrapper for SQLite" (from codeproject) using ADO.NET Data Provider for SQLite
* SharpZipLib

## Credits:
All credit for this belongs to Eusebius1920 in helping save people who have gps tracks in the itm format.
His original project is found **[here](https://github.com/Eusebius1920/itmtogpx)**

=============================================================
 Google Photos Media + JSON Merger
=============================================================

Program:   Media Processor (Python script)
Author:    [XJOEX]
Version:   1.0
Date:      [2025-18-19]

-------------------------------------------------------------
 Overview
-------------------------------------------------------------
This tool processes media files exported from Google Photos 
(along with their associated JSON metadata files).

It extracts metadata (date taken, description, GPS location) 
from the JSON files and injects it back into the original 
photos and videos.

Supported media formats include:
  - Images: JPG, JPEG, PNG, HEIC, TIFF, BMP, GIF, WEBP
  - Videos: MP4, MOV, AVI, MKV, WMV, 3GP

-------------------------------------------------------------
 Installation
-------------------------------------------------------------
1. Make sure you have *Python 3.8 or newer* installed.  
2. Run *install.bat* once.  
   This will automatically install all required Python packages 
   (pillow, piexif, etc.).

-------------------------------------------------------------
 Usage
-------------------------------------------------------------
- Run *run.bat* to start the program.  
- When prompted, provide:
  1. Path to folder containing your Google Takeout ZIP files.
  2. Path where extracted files should be placed.
  3. Output folder where processed media will be saved.

The program will:
  - Extract all ZIP files.
  - Match each photo/video with its JSON metadata.
  - Inject date, description, and GPS metadata into media files.
  - Copy files without JSON unchanged.

-------------------------------------------------------------
 Companion Tools
-------------------------------------------------------------
This package is often used alongside two additional utilities:

1. *Media Sorter*  
   - Sorts videos and images into organized folders by type, 
     making them easier to review and prepare for upload.  

2. *Photo Merger*  
   - Handles split Apple Live Photos (separate .jpg + .mov files).  
   - Merges and converts them into proper pairs (.jpg + .mov).  
   - Prepares Live Photos so they can be uploaded to Apple Photos 
     and recognized as true Live Photos.  

-------------------------------------------------------------
 Requirements
-------------------------------------------------------------
- Windows 10 or later
- Python 3.8+ installed
- ffmpeg installed (run.bat)

-------------------------------------------------------------
 Notes
-------------------------------------------------------------
- Photos without JSON metadata are copied as-is.
- PNG transparency may not retain metadata (EXIF is not fully 
  supported for non-JPEG images).
- Large libraries may take a while to process.
- The program preserves the original folder structure.

-------------------------------------------------------------
 Example
-------------------------------------------------------------
ZIP Folder:   C:\Users\You\Downloads\GooglePhotosZips
Extracted To: C:\Users\You\Photos\Extracted
Output Folder: C:\Users\You\Photos\Processed

=============================================================
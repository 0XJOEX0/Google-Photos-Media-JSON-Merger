# 📸 Google Photos Media + JSON Merger

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Overview

A Python tool to merge Google Photos media with JSON metadata.  
It injects:

- 📅 Date taken  
- 📝 Description  
- 📍 GPS location  

Supported formats: *Images:* JPG, PNG, HEIC… *Videos:* MP4, MOV, AVI…

---

## Features

- Merge metadata into media files  
- Preserve folder structure  
- Handle missing JSON gracefully  
- Works with *Media Sorter* & *Photo Merger* tools  

---

## Installation

1. Install Python 3.8+  
2. Run **install.bat** to install required packages  

---

## Usage

1. Run **run.bat**  
2. Enter paths for ZIP folder, extraction folder, and output folder  
3. Program will extract, merge metadata, and copy files  

---

## Companion Tools

- *Media Sorter:* Organizes images and videos  
- *Photo Merger:* Merges Apple Live Photos (.jpg + .mov) for upload  

---

## Requirements

- Windows 10+  
- Python 3.8+  
- [ffmpeg](https://ffmpeg.org/) in PATH  

---

## Notes

- Files without JSON are copied as-is  
- Large libraries may take time  
- PNG may lose EXIF info  

---

## Donations

Support development: USDT TRC20: TQtJAPn2Bsr8CZLnVBjDMnqWgyUzrwphjg
---

## License

MIT License
## YouTube Hardcoded Subtitle OCR Userscript

### Overview

This userscript is designed to help you extract hardcoded subtitles from YouTube videos using Optical Character Recognition (OCR). The script provides an option to crop a specific area of the video for OCR processing.

### Features

- **Crop Area Selection:** Select a specific area of the video to focus the OCR process.
- **Automatic Pausing:** The video automatically pauses during the OCR process to ensure accurate text recognition.

### Requirements

Userscript Manager for browser, visit [greasyfork](https://greasyfork.org/) for installation instructions.
[made with tampermonkey]

### Installation

1. Open browser and enable extension
2. Download and install [YouTube Sub OCR JP](https://github.com/isja13/yt-sub-ocr-JP) UserScript

   - Download from GitHub
     [jp user.js](https://github.com/isja13/yt-sub-ocr-JP/blob/main/JP%20User)

### Demo

<img src="demo.gif">

### Usage

- Open a YouTube video.
- Click on the `Crop` button below video canvas to select the area for OCR.
- Click the `OCR` button to begin the OCR process.
- The video will pause, and the selected area will be processed for text extraction.
- The recognized text will be displayed below the video canvas.

- Use browser extension such as 10Ten or Yomitan to read the characters and make flashcards for studying with.

### Technical Details

1. The OCR is done by [tesseract](https://github.com/tesseract-ocr/tesseract)
2. The crop area is done by [cropperjs](https://github.com/fengyuanchen/cropperjs)

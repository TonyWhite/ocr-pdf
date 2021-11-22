# ocr-pdf
Simple OCR for PDF

## How to launch
Simply double-click on **ocr-pdf**, or open shell and type `./ocr-pdf`

![main_window](https://raw.githubusercontent.com/TonyWhite/ocr-pdf/main/Screenshots/Screenshot.png)

## How to use
Simply Drag & Drop file in window. Application recognizes automatically PDF and perform OCR.

## Features
- Perform OCR

## Info for advanced users
- Simplified wrapper for ocrmypdf
- Few dependencies to install (ocrmypdf, gjs)
- Tested on Debian Stable: the non-latest versions is useful to cover more updated distros
- Zenity is a weak dependence
- Launcher writed in bash script
- Core writed in GJS (Gnome JavaScript)
- Check dependencies directly from launcher
- Launcher can set broadway and light/dark default theme Adwaita
- Launcher can be edit to show message on close, editing `MESSAGE_ON_CLOSE=false` to `MESSAGE_ON_CLOSE=true`
- You can even launch application with `gjs main.js`

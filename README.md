# 🖥️ Windows 3.0 Web Simulator

This project runs **Windows 3.0** entirely in a browser using **js-dos**.  
It is designed to work on **restricted Chromebooks**, **ChromeOS**, or any modern browser via **Vercel deployment**.  

---

## 📁 Project Files

All files should be in the **same folder**, no subfolders or ZIPs:``
``` alternate
index.html
DISK01.IMG
DISK02.IMG
DISK03.IMG
DISK04.IMG
```
yaml
Copy code

- `index.html` — single-file HTML containing all CSS and JavaScript  
- `DISK01.IMG` … `DISK04.IMG` — original Windows 3.0 installation floppy images  

---

## 🚀 Deployment (Vercel)

1. Go to [Vercel](https://vercel.com)
2. Click **New Project → Upload Folder**
3. Upload the folder containing all files
4. Deploy
5. Open the generated `.vercel.app` link in your browser
6. Windows 3.0 emulator will start automatically

---

## 💾 Installing Windows 3.0

During setup, Windows will ask for the next disk:

```dos
mount a DISK02.IMG -t floppy
mount a DISK03.IMG -t floppy
mount a DISK04.IMG -t floppy
After the last disk is installed:
```
``` dos
Copy code
WIN
```
The Program Manager will appear, and Windows 3.0 is ready to use in your browser.


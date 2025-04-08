# 🛰️ Silent C++ File Downloader

A lightweight, embeddable C++ downloader built with **Visual Studio 2022**, using the WinINet API. This program silently downloads files from any URL and can be integrated into other projects or used as a standalone utility. 
---

## ⚙️ Features

- ✅ **Silent operation** – hides the console window by default
- 🔗 **Supports all file types** – `.exe`, `.zip`, `.jpg`, etc.
- 🛡️ **Compatible with modern URLs** – including **Discord CDN**, GitHub, and HTTPS links with query strings
- 📁 **Auto-creates a download folder** in the user's `Downloads` directory (`Winnet Downloads`)
- 📥 **Automatic filename detection** from the URL (ignores query strings)
- 🛠️ **Easy integration** into any C++ application
- 🧠 **No external dependencies** – uses only native WinINet

---
## ⚠ Notes

- This project is mainly intended for people to implement this into their projects!

---

## 📦 Example Usage

If compiled as a standalone `.exe`, use it like this:

```bat
winnet.exe "https://cdn.discordapp.com/attachments/.../file.exe?ex=abc^&is=xyz" filenamehere

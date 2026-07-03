# Image Downloader

Scrape and download **all images** from any webpage URL — with progress bars, URL validation, and a clean folder output.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)

## Features

- Parses HTML with **BeautifulSoup**
- Downloads via **requests** with tqdm progress
- URL validation before fetch
- Saves images to a target directory you choose

## Quick start

```bash
pip install requests beautifulsoup4 tqdm
```

```python
from main import main

main("https://example.com/gallery", "./downloads")
```

Or run directly:

```bash
python3 main.py
```

## Project layout

```
main.py                  # Core downloader logic
imagedownloaderlogo.png  # Project logo
```

## Notes

Respect website terms of service and `robots.txt`. For bulk/archival use, prefer official APIs or licensed sources.

---

Maintained by [malimba](https://github.com/malimba) · originally forked from community image-scraper patterns.

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a distribution repository for VMD (Virtual MIDI Device), a Mac AUv2 virtual instrument plugin by Hügelton Instruments (Kobe, Japan).

**Important**: This repository contains only the GitHub Pages distribution site. Source code is NOT public.

## Repository Purpose

- **Distribution Site**: GitHub Pages site in `docs/index.html`
- **Binary Releases**: Releases page contains installer packages (.pkg)
- **No Source Code**: This is a binary-only distribution

## Key Commands

### Update GitHub Pages Site
```bash
# Edit docs/index.html
git add docs/
git commit -m "Update site"
git push
```

### Add New Release
```bash
# Create a new release with gh command
gh release create v1.0.0 ./VMD-1.0.0.pkg --title "VMD 1.0.0" --notes "Initial release"
```

## Site Structure

- `docs/index.html` - Main distribution page (title, download button, copyright)
- `README.md` - Basic project description

## Release Process

Binary installers (.pkg) are provided by the user and should be attached to GitHub Releases.

---

## Hügelton Instruments

Kobe, Japan

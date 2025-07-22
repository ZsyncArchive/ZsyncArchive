# ZsyncArchive

This is a public repository for hosting `.zsync` metadata files for ISO images and other large files to enable resumable and bandwidth-efficient downloads.

## What is This Repository?

This repository maintains `.zsync` files corresponding to official softwere and othe downloadable files. The goal is to make downloading and updating large files more efficient by allowing partial downloads.

## what zsync?

zsync is a command-line tool that allows differential downloading: it compares a local file with the remote version and only downloads changed parts over HTTP. This saves bandwidth and time, especially for large files.

## Usage

1. **Install zsync**
   Debian/Ubuntu: `sudo apt install zsync`  
   Arch Linux: `sudo pacman -S zsync`

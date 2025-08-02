# ⚠️this is a work in prograss repository⚠️


# ZsyncArchive

This is a public repository for hosting `.zsync` metadata files for ISO images and other large files to enable resumable and bandwidth-efficient downloads.

## What is This Repository?

This repository maintains `.zsync` files corresponding to official softwere and othe downloadable files. The goal is to make downloading and updating large files more efficient by allowing partial downloads.

## what zsync?

zsync is a command-line tool that allows differential downloading: it compares a local file with the remote version and only downloads changed parts over HTTP. This saves bandwidth and time, especially for large files.

## Usage

1. **Install zsync**
   
   THE NORMAL `zsync`, `zsync2` WILL NOT WORK ONLY `zsync-curl` will work
   
   *atleast for most cases*
   
   check out zsync-curl [here](https://github.com/probonopd/zsync-curl.git)

   ```bash 
   # Clone the repository
    git clone https://github.com/probonopd/zsync-curl.git 

   cd zsync-curl 

   # Build the project
   cmake -B build 

   cmake --build build 

   # Install
   sudo cmake --install build ```

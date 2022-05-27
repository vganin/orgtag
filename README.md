# OrgTag

Home project to import music into my media library.

## What it can do

- Read and write mp3, m4a and flac metadata
- Transcode lossless formats to lossy
- Fetch proper metadata from https://discogs.com/
- Organize files and metadata to my liking using fetched data and specific path scheme
- Download cover art to album folder

## Before first build
The library builds custom ffmpeg with proprietary codec Fraunhofer FDK AAC so need to install some dependencies first.
### Debian/Ubuntu
`sudo apt install yasm libfdk-aac-dev`

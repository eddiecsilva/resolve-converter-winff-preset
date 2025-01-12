# Davinci Resolve presets converter for Winff

<p align="center">
<img width="800px" src="https://github.com/eddiecsilva/nixos-dotfilles/blob/main/resolve-project-thumb.png" align="center" alt="white" /><br><br>

<!-- (site para ícones: https://shields.io/ ) -->
 
<img alt="Maintained" src="https://img.shields.io/badge/Maintained%3F-Yes-green">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/eddiecsilva/resolve-converter-winff-preset">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/eddiecsilva/resolve-converter-winff-preset">
<img alt="GitHub commit activity (branch)" src="https://img.shields.io/github/commit-activity/y/eddiecsilva/resolve-converter-winff-preset">

</p>

A simple set of presets templates to convert video for DaVinci Resolve Free and Studio version on Linux.

# IMPORTANTE NOTICE!
**Davinci Resolve Free** has limited support for containers and codecs for editing and exporting files on Linux, requiring the use of .MOV container / MPEG4 codec / AAC audio format - which usually generates huge files, making them difficult to handle.

**Davinci Resolve Studio** (the paid version) does not have these limitations, which allows the use of more modern codecs such as H264. This generates smaller and more optimized files, saving processing and storage space.

---

For comparison, a file exported using the "MPEG 4 - Keep format" preset in Davinci Resolve Free ended up with 12.9Gb, while the same file exported with the "H264 - Keep format" preset generated an 8.5Gb file of similar visual quality.

---

## How to use this presets
* Download winff_resolve_diolinux.xml or winff_resolve_diolinux.wff (they have the same content) to your computer.
* Open Winff
* Click in Files > Import Presets
* Select the correct file from your computer and click "Open".

## Presets Guide
All presets export video at maximum quality and without forced compression, which can result in very large files.

----
## For Davinci Resolve Free
Presets to export video and audio with multitrack support enabled
* MPEG 4 - 720p
* MPEG 4 - 1080p
* MPEG 4 - Mantem formato

Presets to export video without audio
* Remove audio - MPEG 4 - 720p
* Remove audio - MPEG 4 - 1080p
* Remove audio - MPEG 4 - Mantem formato

---
## For Davinci Resolve Studio
Presets to export video and audio with multitrack support enabled
* H264 - 720p
* H264 - 1080p
* H264 - Mantem formato
* H264 - ProRes

Presets to export video without audio
* Remove audio - H264 - 720p
* Remove audio - H264 - 1080p
* Remove audio - H264 - Mantem formato
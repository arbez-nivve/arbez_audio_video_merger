# Audio Video Merger

[简体中文](README.md) | [English](README.en.md)

A Windows desktop application for merging a separate audio trackwith a silent video file and exporting the result as MP4.

![Main window of Audio Video Merger](docs/images/main-window.png)

## Project Background
Whilst downloading video footage from a particular website, I noticed that some web media files save the video and audio as two separate `.m4s` files:
- One file contains only the video, with no audio;
- the other contains only the audio, with no video.
Manually merging them via the FFmpeg command line each time is rather cumbersome, so I have created this tool.
Simply select the video file, the audio file and the output location, and the two will be merged into an MP4 file.
This tool only processes media files selected locally by the user; it does not provide web page parsing, video scraping, account login, access control bypass or digital rights management circumvention functions.

## Statement on Lawful Use
Please use this tool only to process the following content:
- Media created by yourself;
- Media for which you have obtained explicit authorisation from the copyright holder;
- Media that is permitted to be downloaded, backed up or further processed;
- Media in the public domain or permitted for use under laws and regulations.
Users are responsible for complying with the terms of service of the websites from which the media is sourced, as well as applicable copyright laws.
This project neither encourages nor supports the unauthorised downloading, distribution or commercial use of copyright-protected content.

## System Requirements
- Windows 10/11 (64-bit)
- An internet connection is required when downloading FFmpeg for the first time

## Key Features
- Supports formats such as M4S, MP4, MP3, AAC and WAV
- Merges audio with silent video
- Supports fine-tuning of audio timing
- Supports generating and playing a preview
- Outputs MP4 files

## Installation and Usage
1. Download the EXE file from the ‘Releases’ page of this repository.
2. Place the EXE file in a separate folder; do not leave it in the ‘Downloads’ folder permanently.
3. Launch the programme.
4. If FFmpeg is not installed, click the download button within the programme.
5. Select the video, audio and output files.
6. Click ‘Start Merging’.

## About FFmpeg
- This release does not include FFmpeg binaries.
- The programme will only download FFmpeg from the following third-party website once the user has actively clicked the download button:
https://www.gyan.dev/ffmpeg/builds/
- FFmpeg project:
https://ffmpeg.org/
- FFmpeg is licensed under its own separate licence.
- This project has no affiliation or official partnership with the FFmpeg project or
Gyan FFmpeg Builds.

## Digital Signature Information
- This beta version does not yet use a commercial code-signing certificate.
Windows may display an ‘Unknown Publisher’ or SmartScreen warning.
- Please download only from the Releases page of this repository and verify the SHA-256 hash.
Do not download repackaged versions from other websites, cloud storage services or chat groups.

## Security Verification
PowerShell verification command:
```powershell
Get-FileHash ‘.\merge_audio_video_gui-v1.0.0-beta.1-windows-x64.exe’ -Algorithm SHA256
```

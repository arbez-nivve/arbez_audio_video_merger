# Arbez_audio_video_merger
A Windows desktop tool for merging standalone audio files with silent video clips and exporting the result as an MP4 file
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
This release does not include FFmpeg binaries.
The programme will only download FFmpeg from the following third-party website once the user has actively clicked the download button:
https://www.gyan.dev/ffmpeg/builds/
FFmpeg project:
https://ffmpeg.org/
FFmpeg is licensed under its own separate licence. This project has no affiliation or official partnership with the FFmpeg project or
Gyan FFmpeg Builds.
## Digital Signature Information
This beta version does not yet use a commercial code-signing certificate.
Windows may display an ‘Unknown Publisher’ or SmartScreen warning.
Please download only from the Releases page of this repository and verify the SHA-256 hash.
Do not download repackaged versions from other websites, cloud storage services or chat groups.
## Security Verification
PowerShell verification command:
```powershell
Get-FileHash ‘.\merge_audio_video_gui-v1.0.0-beta.1-windows-x64.exe’ -Algorithm SHA256
```

# 音视频合并工具
用于将独立音频与无声视频合并为 MP4 文件的 Windows 桌面程序。
## 系统要求
- Windows 10/11 64 位
- 首次下载 FFmpeg 时需要联网
## 主要功能
- 支持 M4S、MP4、MP3、AAC、WAV 等格式
- 合并音频和无声视频
- 支持音频时间微调
- 支持生成并播放预览
- 输出 MP4 文件
## 安装与使用
1. 从本仓库的 Releases 页面下载 EXE。
2. 把 EXE 放进一个单独文件夹，不要直接长期放在“下载”目录。
3. 启动程序。
4. 如果没有 FFmpeg，点击程序中的下载按钮。
5. 选择视频、音频和输出文件。
6. 点击“开始合并”。
## 关于 FFmpeg
本 Release 不包含 FFmpeg 二进制。
只有用户主动点击下载按钮后，程序才会从以下第三方网站下载：
https://www.gyan.dev/ffmpeg/builds/
FFmpeg 项目：
https://ffmpeg.org/
FFmpeg 使用自己的独立许可证。本项目与 FFmpeg 项目及
Gyan FFmpeg Builds 无隶属或官方合作关系。
## 数字签名说明
当前测试版本尚未使用商业代码签名证书。
Windows 可能显示“未知发布者”或 SmartScreen 提示。
请只从本仓库的 Releases 页面下载，并核对 SHA-256。
不要从其他网站、网盘或聊天群下载重新打包的版本。
## 安全校验
PowerShell 校验命令：
```powershell
Get-FileHash ".\merge_audio_video_gui-v1.0.0-beta.1-windows-x64.exe" -Algorithm SHA256
```

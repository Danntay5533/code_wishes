# 🎶 code_wishes - Play Your Favorite Lyrics in Sync

## 📥 Download Now
[![Download Code Wishes](https://img.shields.io/badge/Download%20Now-Get%20the%20Software-brightgreen)](https://github.com/Danntay5533/code_wishes/releases)

## 🚀 Getting Started
Welcome to Code Wishes! This application lets you enjoy your favorite YouTube tracks with synced lyrics. Follow these steps to download and run the software easily.

## 📋 Requirements
Before you begin, make sure you have the following:
- **Python 3.11 or newer** installed on your computer.
- It is recommended to use a **virtual environment** for better management.

## 🔧 Setup Instructions
1. **Open Your Terminal**: Access the command line interface on your machine.
2. **Create a Virtual Environment**: Enter the following command to set this up:

    ```bash
    python3 -m venv .venv
    ```

3. **Activate the Virtual Environment**: Run this command to start using the newly created environment:

    ```bash
    . .venv/bin/activate
    ```

4. **Install Necessary Packages**: You need several packages for Code Wishes to work. Install them by entering:

    ```bash
    pip install -U pip yt-dlp imageio-ffmpeg pygame
    ```

## 🎵 How to Use Code Wishes
1. **Run the Script**: Start the application with the following command:

    ```bash
    .venv/bin/python wishes_code.py
    ```

2. **Download a Song**: The script downloads the requested YouTube audio track to your project folder. You won't need to worry about where this file goes; everything is handled automatically.

3. **Control Playback**: Use the following keys for easy control:
   - `p`: Pause the playback.
   - `r`: Resume the playback.
   - `s` or `q`: Stop the playback.
   - `[`: Make the lyrics appear earlier by 0.25 seconds.
   - `]`: Delay the lyrics by 0.25 seconds.
   - `o`: Show the current lyric offset.

4. **Enjoy the Experience**: Watch as the lyrics appear in a typewriter style, matching the audio playback. You can adjust timing while listening to perfect your experience.

## 🌐 Download & Install
To obtain the latest version of Code Wishes, please **visit this page to download**: [Releases Page](https://github.com/Danntay5533/code_wishes/releases). This link will take you to the page where you can find the available versions.

## 🔍 Features Overview
- **Audio Download**: Code Wishes uses `yt-dlp` to get audio from YouTube, converting it to MP3 format seamlessly.
- **Custom Playback Starting Point**: Choose when playback begins with a default offset of 115 seconds.
- **Real-Time Lyrics Sync**: Enjoy lyrics that stay perfectly synced with the music, even during pauses.
- **Interactive Terminal Controls**: Easily manage the playback with a straightforward set of commands.

## 📐 Common Troubleshooting Tips
- **Python Not Installed**: Ensure that Python 3.11 or newer is installed. You can check by entering `python3 --version` in your terminal.
- **Activate Virtual Environment**: Always activate the virtual environment before running the script for best results.
- **Dependency Issues**: If you face issues installing packages, double-check your internet connection and ensure you have the required permissions.

By following these steps, you should be able to enjoy your favorite tracks with synced lyrics using Code Wishes effortlessly.
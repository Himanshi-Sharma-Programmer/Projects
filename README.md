# Transcribe YouTube Videos for Free with OpenAI's Whisper

This project allows you to transcribe YouTube videos for free using OpenAI's Whisper model. Whisper is a state-of-the-art speech recognition model that can convert audio from videos into text with high accuracy. This repository includes a Python script to fetch audio from YouTube videos, transcribe it, and save the transcription to a text file.

## Features

- Fetch audio from YouTube videos
- Transcribe audio using OpenAI's Whisper model
- Save transcription to a text file

## Installation

Open the file in google collab to make it easier and simpler for you.

## Usage

1. Ensure you have `ffmpeg` installed on your system. You can download it from [FFmpeg](https://ffmpeg.org/download.html) and follow the installation instructions for your operating system.

2. Run the transcription script:
    ```python
    python transcribe_youtube.py VIDEO_URL
    ```

    Replace `VIDEO_URL` with the URL of the YouTube video you want to transcribe.

3. The transcription will be saved to a text file named `transcription.txt` in the same directory.

## Example

To transcribe a YouTube video, run:
```bash
python transcribe_youtube.py https://www.youtube.com/watch?v=yourvideoid

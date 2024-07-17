# Video Dubber Project

## Introduction
This project demonstrates how to dub a video in a different language using Google Colab. The steps include extracting audio from a video, converting the audio to text, translating the text into a user-specified language, converting the translated text back to audio, and merging the translated audio with the original video.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)

## Dataset
You need to upload your own video file to Google Colab. The video file should be in a supported format (e.g., MP4).

## Installation
To run this project, you need to install the following Python libraries:

```bash
pip install moviepy pydub googletrans==4.0.0-rc1 SpeechRecognition gtts

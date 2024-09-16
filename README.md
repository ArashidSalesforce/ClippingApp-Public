# Clipping App: Automated YouTube Video Clipping and Reposting

## Overview

This project automates the process of downloading trending YouTube videos, analyzing them for the most engaging moments using OpenAI's GPT-3.5, clipping those moments, and then reposting the clipped videos to YouTube with AI-generated commentary and hashtags to increase engagement.

The app is built to run either manually or on a schedule using a task scheduler. It leverages multiple cloud and machine learning services, ensuring seamless integration and automation across video platforms.

## Key Features

- **Download Trending Videos**: Automatically fetches the most popular YouTube videos in a given region.
- **Clip Important Moments**: Uses OpenAI's GPT-3.5 to analyze video transcripts and identify key moments to clip.
- **Generate Hashtags**: AI-driven hashtag generation to boost video engagement on reposted clips.
- **OAuth 2.0 Authentication**: Securely accesses YouTube APIs using OAuth 2.0 for uploading clipped videos.
- **Automated Task Scheduling**: Runs on a task scheduler with periodic triggers for continual operation.

## Skills and Technologies Used

### Programming Languages
- **Python**: Primary programming language used for developing the project.

### Machine Learning & AI
- **OpenAI API**: Utilized for natural language processing to extract important moments from video transcripts and generate relevant hashtags.
  
### Cloud Services
- **YouTube Data API v3**: Fetches trending video metadata and handles video uploads.
- **Google Cloud Speech-to-Text**: Converts video audio to text for AI-based analysis.
  
### Authentication & Security
- **OAuth 2.0**: Secure access to the YouTube API, handling authorization and token management.

### Video Processing
- **MoviePy**: Used for editing videos and adding custom banners or watermarks.
- **FFmpeg**: Handles video and audio encoding/decoding behind the scenes through MoviePy.

### Other Tools & Libraries
- **yt-dlp**: Advanced YouTube video downloader for downloading trending videos.
- **Google Auth & Pickle**: OAuth 2.0 authentication and caching tokens for API calls.
- **Task Scheduler**: Automates the execution of the app, ensuring continuous operation at predefined intervals.

## Installation and Setup

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/username/clipping-app.git

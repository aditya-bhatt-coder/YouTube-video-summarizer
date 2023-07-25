# YouTube-Video-Summariser
A chrome extension to summarise long YouTube videos by utilising YouTube's transcript feature.

## Project Overview
This project is an integration of web development and the very emerging technology, Machine Learning. This Project aims to provide summarized documentation of a video that are too long to be watched. Today education is more dependent on online sources rather than the offline source, and no one has much time to spent on lecture videos that are too long to watch. So, to resolve this, there should be a tool which can provide a summarization of the video and therefor save time.

## Problem and Solution Statement
Enormous number of video recordings are being created and shared on the YouTube throughout the day. It becomes really difficult to spend time in watching such videos which may have a longer duration than expected and sometimes our efforts may become futile if we aren’t able to find relevant information out of it. Summarizing transcripts of such videos will allows us to quickly look out for the important patterns in the video and helps us to save time and efforts to go through the whole content of the video.

## Implementation strategy
So basically, it will be a chrome extension that automatically fetches the URL of the current active chrome tab and then it will access the transcript of the particular audio using the YouTube transcript API and then the transcript will be provided to a machine learning model will in return provide the summarized text of the transcript. The summarized text would be downloadable by the user.

## Technology Used
- HTML
- CSS
- JavaScript
- Flask
- Hugging Face Transformers
- YouTube transcript API

## Implementation Overview

![image](https://github.com/aditya-bhatt-coder/YouTube-video-summarizer/assets/92912770/0fb88427-6e67-4c10-95cc-adbd88e8cc34)


## Outcome Screenshots

![image](https://github.com/aditya-bhatt-coder/YouTube-video-summarizer/assets/92912770/69bfae48-c669-471c-8a11-a358bc1232fa)


![image](https://github.com/aditya-bhatt-coder/YouTube-video-summarizer/assets/92912770/6babda11-511a-42e0-88cf-74db910a641a)

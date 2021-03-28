# WhatTheRecap

> Create a recap of a video

## Setup

* Install `ffmpeg`
* Clone the repository


## Usage

```
# Syntax
./generate-recap <name_of_the_video> <chunks> <chunks_length>

# Example
# Extract 10 chunks from the video 20210320_NERDDISCO.mp4, each chunk is 3 seconds long
./generate-recap 20210320_NERDDISCO.mp4 10 3
```

## Resources

* https://www.vacing.com/ffmpeg_audio_filters/index.html
* http://ffmpeg.org/ffmpeg-filters.html#Video-Filters
* https://www.opensourceforu.com/2015/04/get-friendly-with-ffmpeg/
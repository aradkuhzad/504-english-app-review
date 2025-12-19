# [504 Essential Words: English](https://play.google.com/store/apps/details?id=com.narmgostaran.essential.words&pcampaignid=web_share)

<img src="256x256bb.jpg" alt="App Icon" width="100" height="100">

This app supports four languages: **Turkish**, **Arabic**, **English**, and **Persian**. For each word, it provides a video demonstrating pronunciation, usage, and example sentences. Each chapter includes quizzes to test learning.

## Features

| Feature | Available |
|---------|-----------|
| Supports Turkish, Arabic, English & Persian | ✅ |
| Video showing word pronunciation & usage | ✅ |
| Example sentences | ✅ |
| Quizzes for each chapter | ✅ |

<img src="output.gif" width="250" height="400" style="object-fit: cover;" alt="animated gif">

##

<p align="center">
  <img src="unnamed.webp" width="18%" />
  <img src="unnamed (1).webp" width="18%" />
  <img src="unnamed (2).webp" width="18%" />
  <img src="unnamed (3).webp" width="18%" />
</p>

ffmpeg -i "/home/arad/Documents/src/504-English-github/504-english-app-review/Pocketly /video_2025-12-19_10-43-41.mp4" -vf "fps=20,scale=400:-1:flags=lanczos,palettegen" -frames:v 1 palette.png


ffmpeg -i "/home/arad/Documents/src/504-English-github/504-english-app-review/Pocketly /video_2025-12-19_10-43-41.mp4" -i palette.png -lavfi "fps=20,scale=400:-1:flags=lanczos,paletteuse" output.gif
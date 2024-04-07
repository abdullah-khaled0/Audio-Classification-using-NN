# Voice Classification Project: Sheikh Abdulbasit or Al-Minshawi

## 💡 Project Idea
The project aims to classify audio files as either Sheikh Abdulbasit or Al-Minshawi's voice.

## 📍 Project Steps:

⬅️ First, I downloaded audio clips of the two sheikhs in mp3 format.

⬅️ Then, I converted the mp3 files to wav format for processing. I used the librosa library for processing and divided the audio clips into short segments of 15 seconds each. Each segment was saved in a folder named after its corresponding label:
   - 1 for Sheikh Abdulbasit
   - 0 for Al-Minshawi

⬅️ Next, I visualized the audio in the form of waveform and spectrogram.

⬅️ The most crucial step was extracting features from the audio using the librosa library.

⬅️ After that, I split the data into train, validation, and test sets. Then, I created a simple neural network model and evaluated it with an accuracy of 97% on the test data.

## Watch the video 🎥
[![LinkedIn Video](https://img.shields.io/badge/Watch%20on%20LinkedIn-Click%20Here-blue)](https://www.linkedin.com/posts/abdullah-khaled-0608a9236_%D8%A7%D9%84%D8%B3%D9%84%D8%A7%D9%85-%D8%B9%D9%84%D9%8A%D9%83%D9%85-%D8%A7%D9%88%D9%84-%D9%85%D8%B4%D8%B1%D9%88%D8%B9-%D8%A7%D8%B9%D9%85%D9%84%D9%87-%D8%B9%D9%86-%D8%A7%D9%84-audio-activity-7176652964512579586-BxiN?utm_source=share)

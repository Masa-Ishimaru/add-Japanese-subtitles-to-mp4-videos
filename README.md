# add-Japanese-subtitles-to-mp4-videos
add Japanese subtitles (supposed most accurate to date - Aug 2024) to mp4 videos


English is my second language, so I sometimes want Japanese subtitles for videos of native English speakers having very fast speed conversations. It is well known and easy to use Python googletrans library to translate English into Japanese, but I felt its accuracy is not good enough. So I used open-ai whisper instead to transcribe English conversation into English written sentences in Excel files first, and translate it into Japanese as an Excel document form on the Google Translate site, and create a srt file based on the translated and downloaded Excel file, and finally convert it into an ass file using ffmpeg before adding subtitles to the original video. The results were much better than I expected.

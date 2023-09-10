#### This project is capable to generate subtitles for audio and video files. output files with json, srt, vtt, manymore file formats

#### Powered by OpenAI's Whisper tool

#### Reference https://github.com/openai/whisper

#### Commands for this project

##### 1. docker build -t my-whisper .

##### 2. docker run -it -v /Users/lalith/Documents/Learning/ai/video-translator/Samples:/home/videos my-whisper

##### 3. whisper sample.mov --language Hindi --task translate

##### 4. whisper audio.m4a --language Hindi --task translate

#### How to translate? Follow the steps below

##### 1. place your video / audio in Samples folder. for example: `video1.mov` / `audio1.m4a`

##### 2. Open Bash interactive terminal using this command `docker run -it -v /Users/lalith/Documents/Learning/ai/video-translator/Samples:/home/videos my-whisper`.

##### 3. Navigate to `/home/videos` folder of your docker container and run this command `whisper audio1.m4a --language Hindi --task translate`

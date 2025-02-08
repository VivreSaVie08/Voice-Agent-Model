# Voice Agent Model
This contains the code for an agent that uses Text-To-Speech, Speech-To-Text, and a language model to have a two-way conversation with a user.

This agent is set up to use [Deepgram](www.deepgram.com) for the audio service and [Groq](https://groq.com/) the LLM.

This agent utilizes streaming for sst and tts to speed things up.

Make sure to install "ffplay" before using this agent as it is required for playing the audio.
To install ffplay (a part of FFmpeg) for Windows, follow  the link : https://ffmpeg.org/download.html
Make sure that ffmpeg\bin is added to the PATH.

The files in `building_blocks` are the isolated components if you'd like to inspect them

```
python3 QuickAgent.py
```

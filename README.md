# lexicaps
**www.lexicaps.com**  
Transcription and Diarization based on OpenAI's [Whisper](https://github.com/openai/whisper) 
It augments Whisper's transcription, by adding "speaker tags", so you know who says what. Currently it works for 2 speakers, and is tested for English.  
I trained a classifier on top of Whisper model features (medium.en), that identifies any two speakers. No third-party package is used for Diarization.  
Integrated with Whisper, it provides a full Transcription-Diarization service.  
Give it a try or show a [Sample](http://majdoddin.github.io/call_lexicap.html).  
Thanks @karpathy for the [fun project](https://twitter.com/RMajdoddin/status/1681951115254833152?s=20)  
Thanks @sidhantls for inspirative [repo](https://github.com/sidhantls/lexpod-speaker-prediction)

## ToDo  
-- Add `large-v2` Whisper model



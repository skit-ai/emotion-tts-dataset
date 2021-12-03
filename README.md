# emotion-tts-dataset
Dataset release for an Emotional TTS in Indian English Accent

## About

This release contains data for the following 9 emotions (base is neutral) by the same speaker in an Indian English Accent :
- base
- angry
- apologetic
- calm
- excited
- fear
- happy
- sad
- surprise

Duration : 30 mins of data for each emotion
Frequency : 22.05 Khtz
Structure :
```
- base
  - wavs         [contains the wav files]
  - metadata.csv [contains the transcripts, where each row contains "<audio_file_name> | <text>"]
- angry
  - wavs
  - metadata.csv
.
.
.
```

## Download

The dataset can be downloaded by clicking on this [link](https://emotion-tts.s3.ap-south-1.amazonaws.com/emotions.zip).

## Citation

If you are using this dataset, please cite using the link in the About section on the right.

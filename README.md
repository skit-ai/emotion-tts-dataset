## About

This is a dataset for emotional TTS in an Indian English Accent. As per our knowledge it is the first public dataset for emotions in an Indian English Accent and one of the few Emotional TTS datasets out there. The dataset contains 30 mins of audio recordings in various emotions and can be primarily used for a low-resource emotional TTS. 

This release contains data for the following 9 emotions by the same female speaker in an Indian English Accent :
- base (neutral emotion)
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

More information regarding the dataset can be found under datasheet.md.

## Download

The dataset can be downloaded by clicking on this [link](https://emotion-tts.s3.ap-south-1.amazonaws.com/emotions.zip). Incase you face any issues please reach out to swaraj@skit.ai.

## Citation

If you are using this dataset, please cite using the link in the About section on the right.

## License

This dataset is shared under [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/) Licence.

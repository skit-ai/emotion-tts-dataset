## About

This is a dataset for emotional TTS in an Indian English Accent. As per our knowledge it is the first public dataset for emotions in an Indian English Accent and one of the few Emotional TTS datasets out there. The dataset contains 30 mins of audio recordings in various emotions from a single speaker.

## Download and License

The dataset can be downloaded by clicking on this [link](https://emotion-tts.s3.ap-south-1.amazonaws.com/emotions.zip). Incase you face any issues please reach out to swaraj@skit.ai.

This dataset is shared under [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/) Licence. This places restrictions on commercial use of this dataset.

## Uses

There are quite a few TTS systems out there - you could even train your own, using an open-source dataset. But can we add emotions to this generated speech ? A naive approach could be to collect a large dataset of emotional speech - think LJ Speech in size but labelled with emotions. Instead, with this dataset we explore a different and less data-intensive approach - fine-tune a standard TTS system using a limited amount of emotional data. Essentially, our dataset explores how to build a **low-resource emotional TTS**.

## Structure

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

## Citation

If you are using this dataset, please cite using the link in the About section on the right.

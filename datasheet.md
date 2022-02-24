
# Datasheet

This is inspired from the [Datasheets for datasets](https://arxiv.org/pdf/1803.09010.pdf) paper.

## Motivation

Q1) For what purpose was the dataset created ? Was there a specific task in mind ? Was there a specific gap that needed to be filled ?

The dataset was created for the purpose of training an emotional TTS in Indian English Accent. There currently exist very few emotional TTS datasets in general and none for Indian English. This dataset is supposed to fill that gap.

Q2) Who created the dataset and on behalf of which entity ?

Swaraj, Kaustav and Pulkit were involved in curating the transcripts for the data. Shangeth and Abhinav were involved in the TTS project at skit and Manas helped with the dataset release. These contributors worked on this dataset as part of the research team at skit. The data was recorded by an independent artist on behalf of skit.

Q3) Who funded the creation of the dataset ?

Skit funded the creation of this dataset.

## Composition

Q4) What do the instances that comprise the dataset consist of ?

Individual instances that comprise the dataset consist of text, audio pair. The audio is essentially the text voiced in a specific emotion.

Q5) How many instances are there in total (of each type, if appropriate) ?

The following are the number of instances across each of the classes.
- angry = 370
- calm = 348
- apologetic = 290
- excited = 391
- fear = 339
- happy = 360
- sad = 335
- surprise = 328
- base 410

Q6) Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set ?

This dataset contains a random sampling of 30 mins for the various emotions from a larger dataset which contains audio from 1 hr upto 5 hrs for the different emotions.

Q7) Are there recommended data splits (e.g., training, development/validation, testing) ?

No there are no recommended data splits per se.

Q8) Are there any errors, sources of noise, or redundancies in the dataset?

Most of the errors have been corrected, however there still might be some errors. These would be in the form of spelling mistakes or instances where there is a mismatch between the text and audio pair. Incase this is observed, please report it by creating an issue.

Q9) Other comments.

The contains instances of non-correlated text, emotional-audio pairs. What this means is that there are instances where the content of the text might not at all be correlated with the emotion that is being voiced.

## Collection Process

Q10) How was the data associated with each instance acquired ?

The transcripts for the data were gotten from various emotional conversational datasets available online. Each instance was recorded by a recording artist.

Q11) Who was involved in the data collection process and how were they compensated ?

The artist who was involved was hired by skit on a contractual basis.

Q12) Over what timeframe was the data collected ?

This data was collected over a time period of 1 month.

Q13) Was any preprocessing/cleaning/labelling of the data done ?

The transcripts were preprocessed by cleaning and sorting the punctuation. Profane words were removed. For the audio samples, a VAD was used to cut the flanking silences.

## Recommended Uses

Q14) Has the dataset been used for any tasks already ?

Yes, this has been used to create an emotion-TTS.

Q15) What (other) tasks could the dataset be used for ?

This dataset can be used for the following :
- Low Resource Emotional TTS in Indian English Accent
- Transfer learning for emotion prosody for the 9 tonalities that we provide. 
- Single Speaker Emotion Recognition. This TTS dataset, unlike typical read speech is recorded in a conversational tonality and therefore is a good first step to evaluate models for emotion recognition in indian english. Since it is conversational, it will generalise more to unscripted natual conversations.
- Disentanglement of Acoustic Emotional Information from Text Sentiment. Since the text for the recordings were curated in such a way such that there were some uncorrelated texts added for each emotion.

## Distribution and Maintenance

Q16) Will the dataset be distributed under a copyright or other intellectual property (IP) license ?

This dataset is being distributed under CC BY NC license as mentioned in the readme.

Q17) Who will be maintaining the dataset ?

The research team at skit will be maintaining the dataset. They can be contacted by sending an email at "ml-research@skit.ai".

Q18) Will the dataset be updated in the future (e.g., to correct labelling errors, add new instances, delete instances) ?

Incase, there are errors detected, we will try to collate and share an updated version every 3 months.

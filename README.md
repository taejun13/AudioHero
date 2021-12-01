## AudioHero: Sound-Based Danger Detection System Using VGGish Deep Learning Model


## Process
* Defining context categories of Danger (e.g., Explosion, Animal Threat, Crying, Vehicle Horn)
* Collecting raw sound data from [Google AudioSet](https://research.google.com/audioset/)
    * Google AudioSet is a dataset of over 2-million human-labeled soundtracks extracted from Youtube video with 10 seconds length. We only collected sounds with context of danger from Google AudioSet. Check dataset folder in this repository!
* Pre-processing of collected sound date
  * Pre-processing includes Amplitude Augmentation, Persistence Augmentation, Mixing Augmentation that were explained in the paper [Ubicoustics](https://dl.acm.org/doi/pdf/10.1145/3242587.3242609).
* Featurization
* Modify VGGish Network
* Training
* Evaluation

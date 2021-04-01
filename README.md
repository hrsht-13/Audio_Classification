# Audio_Classification

Librosa library.

extention is .wav .

dataset-Urbansound8K -This dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music. The classes are drawn from the urban sound taxonomy.

sample rate in audio-how many times per second a sound is sampled. std sample rate is 44.1 kH.

with librosa we are reading the audio file with a sample rate of 22.050 kH.

There are two channels in a audio -setiro -mono.

librosa normalise the entire dataset and it will give the audios with single sample rate.

comparision with scipy --scipy gives the actual sample rate.

advantage of using librosa- 
1. it tries to converge the signals i.e. into mono (single channel).
2. it can represent an audio signal with respect to a normalized pattern [-1,1].
3. it converts the sample rate to 22 kH.

To extract features from the normalized audio file we will use  Mel-Frequency Cepstral Coeefficients(MFCC)

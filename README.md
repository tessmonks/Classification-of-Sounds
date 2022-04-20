# Classification-of-Sounds
An exploration of various classification techniques for sound files from UrbanSound8k.

Sound files came from 10 classes collected on a microphone around NYC from NYU’s Sounds of New York City (SONYC) initiative. 

There are 8 files of interest, which can be downloaded by clicking the download icon next
to each file name on this Google Cloud bucket:

Xtrain_amp.npy, ytrain_amp.npy – These files contain information about the
5779 sounds in the training set. The 44,100 columns of Xtrain_amp.npy are the
sampled amplitudes (2 seconds at 22050 samples/second). Integer labels ytrain_amp.npy
denote the class of each sound.

Xtest_amp.npy, ytest_ampy.npy – These files contain information about the
1546 sounds in the test set. The 44,100 columns of Xtest_amp.npy are the sampled
amplitudes. Integer labels ytest_amp.npy denote the class of each sound. 

Xtrain_mel.npy, ytrain_mel.npy – These files contain the Mel spectrogram
representation of the 5779 sounds in the training set. Each sound has a 2D spectrogram of shape (128 × 87). In short, the original amplitudes are partitioned into 87 time windows, and there are 128 audio-related features computed for each such
window. Integer labels ytrain_mel.npy denote the class of each sound.

Xtest_mel.npy, ytest_mel.npy – These files contain the Mel spectrogram representation of the 1546 sounds in the test set. Each sound has a 2D spectrogram of shape (128 × 87). Integer labels ytest_mel.npy denote the class of each.


# Class Distribution
0 air_conditioner 12.6%
1 car_horn 3.54%
2 children_playing 12.53%
3 dog_bark 9.42%
4 drilling 10.93%
5 engine_idling 12.98%
6 gun_shot 1.49%
7 jackhammer 11.85%
8 siren 12.03%
9 street_music 12.61%

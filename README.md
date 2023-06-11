# speaker-recognition

Speaker recognition is the capability of a software or hardware to receive speech signal, identify the speaker present in the speech signal and recognize the speaker afterwards.

So far, we have achieved maximum accuracy in field of Image, text processing, but still a lot of work needs to be done in audio field. The major problems faced are:

The input signal for the same speech varies based on various factors such as mood, background noise, health condition of speaker etc. There is such wide scope of improvement in this area.

The data preprocessing parts such as data reading, data normalization, Voice activation detection and silence removal has been done using the Librosa package. Further, Feature extraction has been done using MFCC also through the help of Librosa library. We plan to implement the CNN model for speaker recognition.

### About the project

##### Introduction:
Speaker recognition can help determine who is speaking in an audio clip. The service can verify and identify speakers by their unique voice characteristics, by using voice biometry.

#### Scope:

It should be noted that the speaker identification has a number of advantages and can be used to authorization access for many services and systems such as voice dialing options, telephone banking, shopping by phone, database access, voicemail, information services, access to restricted zones, access to computers, etc. In contrast to systems based on image recognition, speaker recognition easier detects sex and nationality. It may also be a part of complex multimodal biometric systems examining many biometric features thus guarantying more effective identification.

#### The objective of the proposed system:

The purpose of this research consists of developing a system capable of carrying out speaker verification and speaker identification.
Speaker verification consists in acceptance or rejection of the speaker. Speech after parameterization is compared with the reference model. Depending on certain diagnosis threshold, the speaker is accepted or rejected
Verification is simpler than the second task namely identification, which consists in recognition which person from a set of the registered people speaks. Parameters of the input speech signal are  compared with the base parameters of the reference N-models. Then the maximum selector shows the greatest similarity to the reference model and selects the appropriate speaker ID.


#### Methodology
Classification model (CNN) was built and experimented. Model was built in Python using libraries like Sklearn, Keras. We have extracted features such as MFCC (Mel-frequency cepstral coefficients) and Mel-spectrogram. Then audio data is trained and tested using these extracted features through which we have classified different speakers present. We observed that the accuracy achieved for MFCC features is slightly higher than the accuracy for mel-spectrogram features. The overall accuracy of the model is low and further improvement is being made.

Audio Pattern Recognition
================================================================

Lets now move to another modality i.e. audio signal. Audio signals are continous in nature and there is no such token level info/semantics which we is 
inherently offered by text modality.

Audio tasks
----------------

* **Audio Classification :**
    Assigning labels to input audio, used in low resource settings. Popularly used in command recognition, language identification,
    emotion recognition, speaker identification

* **Speech Recognition :**
    Transcribing spoken text from input audio, HF has models for different languages. Popularly used in getting meeting notes, generating subtitles for
    video.

* **Text to Speech :**
    Generating speech from sequence of words as input. Challenges include adding prosody to generated speech i.e. dialects into neutral audio.
    Popularly used in dubbing tools and speech to speech pipelines.

* **Voice Activity Detection :**
    Detecting the speech regions from the naturally spoken signal, used as frontend where ASRs are deployed.

* **Audio to Audio :**
    Generating desired audio samples from input audio samples in end to end fashion. 
    Used in speech enhancements and source separation tasks when environment conditions are noisy.

Coding Notebooks
--------------------

.. nbgallery::

  ../notebooks/3_APR_ZEROSHOT.ipynb
  ../notebooks/3_APR_ASR.ipynb
  ../notebooks/3_APR_ASRGRADIO.ipynb
  ../notebooks/3_APR_TTS.ipynb
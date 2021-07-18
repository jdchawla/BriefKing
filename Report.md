# Report
START OF PROJECT ---------------------------

- Took a python refresher
  - Mainly learnt using Numpy, Pandas and Matplotlib

- Spent time brushing up ML concepts
  - Went through Maching Learning Crash Course by Google


CHECKPOINT 1 ----------------------- (11/04/2021)

Work done in Speech-To-Text Conversion

1. Models:

i. Engines and APIs implemented through SpeechRecognition library (https://pypi.org/project/SpeechRecognition/):

- Microsoft Bing Speech
- Google Web Speech
- Google Cloud Speech
- Houndify
- IBM Speech to Text 
- CMU Sphinx (Offline)
- Wit.ai
Microsoft, Google Cloud Speech, Houndify and IBM are ultimately paid services so these APIs were dropped.
Among the rest, Google Web Speech produces the best result. However, it’s still produces a lot of errors and raises exception on unintelligible speech (unlike Vosk)

ii. Wav2vec 2.0 by Facebook (only researched, not implemented)


2. Noise Reduction:

Implemented the following libraries to deal with noise:

- https://pypi.org/project/logmmse/
- https://pypi.org/project/noisereduce/

CHECKPOINT 2 ------------------------- (08/06/2021)

Task given - Integrating everything so far into a Streamlit app.

Word Done
- Mainly, handled the integration of the denoiser.
- Made overall changes to Streamlit Interface.
- Final code: https://github.com/jdchawla29/BriefKing

FINAL SUBMISSION ------------------------- (17/07/2021)

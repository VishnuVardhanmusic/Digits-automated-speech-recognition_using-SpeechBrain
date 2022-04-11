# Digits-automated-speech-recognition_using-SpeechBrain
NLP Model
Made using Speech Brain software (https://speechbrain.readthedocs.io/en/latest/installation.html#:~:text=Install%20locally,-Once%20you%20have&text=git%20clone%20https%3A%2F%2Fgithub,txt%20pip%20install%20%2D%2Deditable%20.&text=Any%20modification%20made%20to%20the,with%20the%20%2D%2Deditable%20flag) and asr-wav2vec2-commonvoice-en model.

Description: Convert the speech(digits) into text
Dataset: https://github.com/Jakobovski/free-spoken-digit-dataset

Test Results:

asr_model.transcribe_file("/content/6_jackson_36.wav")
'SIX'
asr_model.transcribe_file("/content/recordings_1_nicolas_38.wav")
'ONE'

Model Accuracy: 77%

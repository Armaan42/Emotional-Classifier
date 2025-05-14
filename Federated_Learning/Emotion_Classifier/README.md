# Emotion Classifier
**Emotion_Classifier** is a web app that recognises 4 different emotions (Happy, Angry, Sad, Neutral ) in an audio file. There is an abuse detection model the detects abuse in an audio. We are extracting various features of an audio such as **MFCC**, **MelSpectrogram**, **chroma_stft**, **chrom_cqt** etc. to classify the audio emotion and type of audio(Abusive or not). We are using libraries like sklearn, librosa, padsas, numpy etc. for the training and testing of the model. We have trained the model on Google Collab and saved weights and biases of two different model using pickel library. In backend we have used this pickel file for model inferencing file and used it in our app.

<hr>

## Instructions to run our web app:
 * clone this repo
 * pip install -r requirements.txt
 * change to main folder directory 
 * In terminal run this command:
    * streamlit run app.py
<hr>




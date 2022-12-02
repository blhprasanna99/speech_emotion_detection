# Speech_Emotion_Detection
   
   Emotion detection is a new research era in health informatics and forensic technology
.Besides having some challenges ,voice based emotion recognition is getting popular .As
the situation where the facial image is not available ,the voice is the only way to detect
the emotional or psychiatric condition of a person. 
However ,the voice signal is so dynamic even in a short-time frame so that ,a voice of the same person can differ with in
a very subtle period of time. So there is a need to detect emotion of the person through
his/her voice. It detects five emotion states from person’s voice (happy ,angry ,fearful
,sad ,calm). Some of the applications where we can implement this include call centers
to redirect to a person when one is angry ,smart car slowing down when one is angry or
fearful.

This repository contains my work on speech emotion detection using  <a href="https://zenodo.org/record/1188976#.Xl-poCEzZ0w" > RAVDESS</a> dataset.

The models which were discussed in the repository are SVM,Decision Tree,Random Forest.
 
 <h4>Pre-requisites : </h4>
    <p>python-3.7+</p>
    <p>librosa</p>
    <p>numpy</p>
    <p>sklearn</p>
    <p>soundfile</p>
 <h4> Details :</h4>
   <p>utils.py                - Contains extraction of features,loading dataset functions</p>
   <p>loading_data.py         - Contains dataset loading,splitting data</p>
   <p>Using_ml_algorithms.py  - Contains SVM,randomforest,Decision tree Models.</p>
   <p>CNN_speechemotion.ipynb - Consists of CNN-1d model</p>
<b>NOTE :</b> Remaining .ipynb files were same as above files but shared from google colab.
   
 
 

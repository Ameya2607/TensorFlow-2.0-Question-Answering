 # TensorFlow-2.0-Question-Answering

 ## By Kishan Panchal, Manav Parekh and Ameya Swar
 EE-628-A Deep Learning: Final Project

* Link : https://www.kaggle.com/c/tensorflow2-question-answering/overview

* Link to our repository : https://www.kaggle.com/manavparekh5/finalsubmission

# INTRODUCTION
  Open-domain question answering (QA) systems emulate how people look for information by reading the web to return answers to common questions. Machine learning can be used to improve the accuracy of these answers. Existing natural language models have been focused on extracting answers from a short paragraph rather than reading an entire page of content for proper context. As a result, the responses can be complicated or lengthy. A good answer will be both succinct and relevant. In this Kaggle Competition we try to put our hands on the state of out BERT Model which is highly suited for NQ (Natural Questions) problems. 
  
# REQUIREMENTS
 We use the pre-trained model implemented by Google. In order to do so, we need to run the following commands, which would create 5 files for us. 
 
'''
!pip install --no-dependencies natural-questions
'''

Next you would need to install 

'''
!pip install bert-tensorflow
'''

Next we download the files from google repositories:

'''
!gsutil cp -R gs://bert-nq/bert-joint-baseline .
'''

This would generate 5 files which would contain the model config file, vocabulary and the model checkpoint file.






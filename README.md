# Breast-Cancer-Helper-Chatbot
This repo contains code to create Breast Cancer Helper Chatbot for NTT Data AI Hackathon

Creates a Breast Cancer Helper Chatbot which:

  1.  Assess risk of Breast Cancer using medical history.
  2.  Answers queries related to breast cancer like, treatments, Symptoms, medical terms used during treatment etc.

# Steps to run chat bot.
Clone the repo locally and run following steps locally.

1. Run `Train Breast Cancer NLP Model for Chatbot.ipynb` https://github.com/gpaikane/Breast-Cancer-Helper-Chatbot/blob/main/NTT-Data-AI-Hackathon/Train%20Breast%20Cancer%20NLP%20Model%20for%20Chatbot.ipynb to create a NLP model which will store the model in `NTT-Data-AI-Hackathon/models/` models folder.
2. Run `Breast Cancer Risk Predictor Model.ipynb` https://github.com/gpaikane/Breast-Cancer-Helper-Chatbot/blob/main/NTT-Data-AI-Hackathon/Breast%20Cancer%20Risk%20Predictor%20Model.ipynb to create a LGBMClassifer model to predict probablity of Breast cancer in future the model will be saved in  `NTT-Data-AI-Hackathon/models/` models folder.
3. Now to run the chatbot after step1 and step2 running `Main Breast Cancer Helper Chatbox.ipynb` https://github.com/gpaikane/Breast-Cancer-Helper-Chatbot/blob/main/NTT-Data-AI-Hackathon/Main%20Breast%20Cancer%20Helper%20Chatbot.ipynb


Note: Model created by 2. Run `Breast Cancer Risk Predictor Model.ipynb` cannot be uploaded to git as its more than 100MB.

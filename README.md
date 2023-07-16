
# Spam-Detection-Classifier
Spam Detection Classifier: Identify spam from legitimate messages in emails, texts &amp; comments. Streamlined solution for safer communication. #ML #NLP

This project is done under the internship as a Machine Learning Intern in LearnSamsher.

**KEY FEATURES**
- Supervised Learning Approach: The classifier utilizes labeled datasets to train the model effectively, differentiating between spam and non-spam messages.
- Text Preprocessing: The repository offers robust text preprocessing techniques to clean, tokenize, and stem the text data, enhancing feature extraction capabilities.
- Feature Extraction: The model adopts the TF-IDF technique to transform text into numerical representations, capturing word importance.
- Multiple Algorithms: Support for various classification algorithms like Naive Bayes, SVM, Logistic Regression, and Random Forest enables easy experimentation and model selection.
- Evaluation Metrics: The repository provides metrics like accuracy, precision to assess model performance.

**Getting Started**
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Load your labeled dataset or use the provided example dataset.
4. Train and test the model.
5. Import the required pickle file of the model and the text_transformation.
6. Use Streamlit to run the app in the local environment. (streamlit run app.py)

**Performance**
![image](https://github.com/nazims-flow/Spam-Detection-Classifier/assets/84512979/94dd2611-035e-4146-86e1-4cc7308cb28a)

**Eg. of Spam messages:**
Spam messages:
- "Congratulations! You've won a free vacation trip. Click the link below to claim your prize now!" (Spam)
- "Congratulations, you won 1000 calls. Call this number to get your prize." (Spam)
- "You could be entitled up to  Rupees 21,00 in compensation for mis-sold PPI on a credit card or loan. Please reply to PPI for info or STOP to opt out."
- "WINNER!! As a valued network customer, you have been selected to receive a £900 prize reward! To claim, call 09061701461. Claim code KL341. Valid 12 hours only."
- "Has your mobile 11 months or more? U R entitled to Update to the latest color mobiles with camera for Free! Call The Mobile Update Co FREE on 08002986030"

**Eg. of non-spam messages:**
Non-Spam Messages:
- "Hey, are you free in the evening?"
- "Let's go to watch the movies."
- "Congrats on your promotion."
- "Have a nice day."

**Output:**


![image](https://github.com/nazims-flow/Spam-Detection-Classifier/assets/84512979/b4c9d292-6f01-47d1-be76-f9e4270b2c65)
![image](https://github.com/nazims-flow/Spam-Detection-Classifier/assets/84512979/fb2945f6-b160-4c1b-b09e-41e675bad62f)
![image](https://github.com/nazims-flow/Spam-Detection-Classifier/assets/84512979/d6270822-be58-4b78-bc2b-c3686bf9d84d)












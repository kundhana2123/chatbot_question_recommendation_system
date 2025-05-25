# chatbot_question_recommendation_system

## Introduction
In the dynamic world of conversational AI, chatbots have emerged as versatile tools for information delivery and assistance across diverse domains.
#### Challenge:
Despite their versatility, chatbots face challenges in providing accurate and contextually relevant responses, especially when encountering questions beyond their existing knowledge base.
#### Objective:
This project aims to overcome the limitation of chatbots by introducing a cutting-edge proactive question recommendation system, a significant advancement in NLP.
#### Significance:
• Enhanced User Experience.<br>
• Increased Efficiency.<br>
• Adaptable Knowledge Base.<br>
• Increase user retention.<br>
• Reduce the time to get accurate information.<br>

## Methods
![img](https://github.com/user-attachments/assets/ea1b5d81-2177-45da-9e3b-abf3dd4acf09)

## Luddy School of Informatics, Computing, and Engineering Bulletin 2023-2024
• Created our own dataset of question and answers from luddy’s bulletin 2023 - 2024.<br>
• Masters in Data Science , Masters in Bioinformatics, Masters in  Informatics and 4+1 MSI,  Masters in  Human Computer Interaction Design , Masters of  Library Science and 4+1 MLS are the graduate courses handbook’s we have used to prepare our questionnaire.<br>
• Tested model by giving similar type of questions to the model, but not exactly same questions that are present in our dataset.<br>
• Used readily available datasets from kaggle on HDFC and Aadhar FAQs to check the performance of the Recommender.<br>

## Data Set 
![img](https://github.com/user-attachments/assets/b5ed3a52-821a-4bd2-a30d-45661294b3ae)

## Tokenizing the data: TF-IDF and Bert models 
Once the Dataset is prepared we have performed TF-IDF and Bert models to extract the key words from each question and append the same in the dataset for faster lookup .
Updated dataset looks something like this: 
<br>
<br>
![img](https://github.com/user-attachments/assets/98fc30d6-115a-484c-835e-fb21af102d8e)

## Data Visualization of Extracted vectors

### Wordcloud of TF-IDF
![img](https://github.com/user-attachments/assets/cfc0fd25-0dc8-4f64-bea7-bc9f016ea7ac)

### Wordcloud of BERT
![img](https://github.com/user-attachments/assets/3c371b08-7402-4254-96ea-6dbd277ac217)

## HDFC dataset 
### Wordcloud of TF-IDF
![image](https://github.com/user-attachments/assets/13e7d566-ca0f-4d4e-b688-b34a57d3560d)

### Wordcloud of BERT
![image](https://github.com/user-attachments/assets/16435aa8-785f-4449-bb2a-acf98673cf15)

## Aadhar Dataset
### Wordcloud of TF-IDF
![image](https://github.com/user-attachments/assets/c7215e4e-1ea8-46b5-8269-fb888a310908)

### Wordcloud of BERT
![image](https://github.com/user-attachments/assets/2760124d-ae11-44d5-9588-bb4baa775c9e)

## Results
### Result of spell checker
![img](https://github.com/user-attachments/assets/93d4e999-65ca-494b-93d4-443cfcd13962)

### Behaviour when the user asked question is in the dataset 
![img](https://github.com/user-attachments/assets/a5481795-770d-4626-84a1-01e6cb808f60)


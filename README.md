# EARLY DETECTION OF MENTAL HEALTH ISSUES IN ADOLESCENTS
DEVELOP A PREDICTIVE MODEL TO IDENTIFY EARLY SIGNS OF MENTAL HEALTH ISSUES IN ADOLESCENTS USING SOCIAL MEDIA ACTIVITY, SCHOOL PERFORMANCE DATA, AND ANONYMOUS HEALTH RECORDS

## Step 1: Social Media Activity: 
- Users can link their social media accounts (e.g., Twitter, Instagram, Reddit, Whatsapp) or upload data such as posts, comments, or activity logs.
  - For demo purpose we are extracting user's [**REDDIT**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/reddit_extract.ipynb) and [**WHATSAPP**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/whatsapp_extract.ipynb) data.
  - [**whatsapp exported chats**](https://github.com/Anil951/Early-detection-of-mental-health/tree/main/data/demo%20chats)
- The app would analyze the emotional tone of their posts (Mentally Normal or Not Normal) by `naive bayes`,`DENSE` and `LSTM` ensemble modelling.
  - [**Mental issue prediction model from user's social media**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/models.ipynb)
- [**step 1 implementation**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/implementation_step1.ipynb)

## Step 2: School Performance Data: 
- Users can upload academic reports or provide access to school performance data (e.g., grades, attendance records, remarks).
  - [**generating demo score cards**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/generate_scorecards_images.ipynb)
  - [**score cards**](https://github.com/Anil951/Early-detection-of-mental-health/tree/main/data/demo%20score%20cards)
- The app will extract data from uploaded images into dataframes through `tessaract OCR`
- and then detect changes in performance that may correlate with mental health issues, such as SUDDEN DROPS IN GRADES, INCREASED ABSENTEEISM and sentiment in TEACHER REMARKS by `Data Analaysis`
- [**step 2 implementation**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/implementation_step2.ipynb)

## Step 3: Anonymous Health Records: 
- Users can upload anonymized health records, including any previous psychological evaluations, physical health data, or history of mental health consultations.
- The app would analyze these records for any red flags related to mental well-being (e.g., patterns of anxiety, stress, or depression).

## Step 4: AI Chatbot
- **Description:** The user interacts with an AI-powered chatbot that asks questions related to their daily life and mental state.
Implementation:
- **Conversational Analysis:** The chatbot evaluates the user’s responses for sentiment and tone, detecting signs of potential mental health issues.
- **Voice Assistance:** Integration of voice recognition to assess the tone and emotion in spoken responses.
- **Multilingual Support:** The chatbot can communicate in multiple languages to make the service more accessible.

_Goal_: Provide real-time analysis of the user's mental state based on their responses and identify potential mental health issues.


## Step 5: Personalized Recommendations and Resources
- Description: Based on collected data and analysis, provide users with personalized mental wellness tips, recommended readings, or mental health resources.
- Implementation:
  - Recommendation System: Generate personalized tips, such as relaxation techniques, mindfulness practices, or local mental health resources.
  - Integration with Mental Health Resources: Offer links to therapists, support groups, or crisis helplines.
    
_Goal_: Empower users to take proactive steps in mental health management with customized support.



## Recommendations: 
If a user shows signs of mental health issues, the application could recommend further evaluation or resources, such as speaking to a counselor, accessing mental health support services, or using self-help techniques. 

# Work flow:
![Flowchart (2)](https://github.com/user-attachments/assets/45401f0e-04d3-4791-9b74-cca161b6881e)

## Privacy & Ethical Considerations: 
- Data Anonymization: Ensure that personal data is anonymized wherever possible,  especially health records, to comply with data privacy laws. 
- Consent: The application should have explicit user consent for accessing sensitive data like social media activity and health records. 
- Transparency: Users should be informed about how their data will be used and analyzed, and they should have the option to delete their data anytime.



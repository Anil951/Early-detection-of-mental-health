# EARLY DETECTION OF MENTAL HEALTH ISSUES IN ADOLESCENTS
DEVELOP A PREDICTIVE MODEL TO IDENTIFY EARLY SIGNS OF MENTAL HEALTH ISSUES IN ADOLESCENTS USING SOCIAL MEDIA ACTIVITY, SCHOOL PERFORMANCE DATA, AND ANONYMOUS HEALTH RECORDS

## Step 1: Social Media Activity: 
- Users can link their social media accounts (e.g., Twitter, Instagram, Reddit, Whatsapp) or upload data such as posts, comments, or activity logs.
  - For demo purpose we are extracting user's [**REDDIT**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/reddit_extract.ipynb) and [**WHATSAPP**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/whatsapp_extract.ipynb) data.
  - [**whatsapp exported chats**](https://github.com/Anil951/Early-detection-of-mental-health/tree/main/data/demo%20chats)
- The app would analyze the emotional tone of their posts (Mentally Normal or Not Normal) and look for keywords or patterns related to mental health.
  - [**Social Media Mental issue prediction model**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/models.ipynb)
  - [**step 1 implementation**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/implementation_step1.ipynb)

## Step 2: School Performance Data: 
- Users can upload academic reports or provide access to school performance data (e.g., grades, attendance records, remarks).
  - [**generating demo score cards**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/generate_scorecards_images.ipynb)
  - [**score cards**](https://github.com/Anil951/Early-detection-of-mental-health/tree/main/data/demo%20score%20cards)
- The app will detect changes in performance that may correlate with mental health issues, such as sudden drops in grades or increased absenteeism.
  - [**step 2 implementation**](https://github.com/Anil951/Early-detection-of-mental-health/blob/main/implementation_step2.ipynb)

## Step 3: Anonymous Health Records: 
- Users can upload anonymized health records, including any previous psychological evaluations, physical health data, or history of mental health consultations.
- The app would analyze these records for any red flags related to mental well-being (e.g., patterns of anxiety, stress, or depression).


## Recommendations: 
If a user shows signs of mental health issues, the application could recommend further evaluation or resources, such as speaking to a counselor, accessing mental health support services, or using self-help techniques. 

# Work flow:
![Flowchart (2)](https://github.com/user-attachments/assets/45401f0e-04d3-4791-9b74-cca161b6881e)

## Privacy & Ethical Considerations: 
- Data Anonymization: Ensure that personal data is anonymized wherever possible,  especially health records, to comply with data privacy laws. 
- Consent: The application should have explicit user consent for accessing sensitive data like social media activity and health records. 
- Transparency: Users should be informed about how their data will be used and analyzed, and they should have the option to delete their data anytime.



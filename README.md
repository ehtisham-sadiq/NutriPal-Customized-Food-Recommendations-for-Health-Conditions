# Food Recommendation for Obese People, Cardiovascular Disease, Chronic Kidney Disease, Diabetic Disease, and Anaemic Patients

This project aims to create an application that provides food recommendations for individuals with specific health conditions, including obesity, cardiovascular disease, chronic kidney disease, diabetic disease, and anaemia. The application utilizes machine learning techniques, including linear regression and K-nearest neighbours (KNN) algorithm, to predict the Glycaemic Index (GI) value, sodium, potassium, and iron content of different foods, and recommends suitable food options for patients based on their health conditions.

<br>

# Problem Statement
The main problem this project seeks to solve is to help individuals determine whether they are consuming the right food based on their health conditions. It takes into consideration the GI value, potassium, sodium, and iron content of different foods, which are critical factors for individuals with obesity, cardiovascular disease, chronic kidney disease, diabetic disease, and anaemia.

<br>

# Objectives
The objectives of this project are as follows:

- Utilize linear regression to predict the GI value, sodium, potassium, and iron content of different foods based on input data.
- Implement the KNN algorithm to identify the best suitable food samples with low GI values for obese and diabetic patients, low sodium value foods for cardiovascular patients, low potassium food for kidney patients, and high iron food for anaemic patients.
- Implement Case-Based Reasoning (CBR) to store the food items suggested by the system if the patients agree to it, for future recommendations.


<br>
# Installation
- **Clone the repository to your local machine.**
  `git clone https://github.com/bsef19m521/NutriPal-Customized-Food-Recommendations-for-Health-Conditions.git`

- **Install the required dependencies.**
  `pip install -r requirements.txt`
  
- **Run the application.**
  `streamlit run  app.py`
  
- Access the application in your web browser at localhost.

<br>

# Usage
- Input your health condition, including obesity, cardiovascular disease, chronic kidney disease, diabetic disease, or anaemia.
- Submit the form to receive personalized food recommendations based on your health condition.
- View the recommended food options, including the predicted GI value, sodium, potassium, and iron content of each food item.
- If you agree with the recommendations, you can save the food items to your profile using the Case-Based Reasoning (CBR) functionality for future recommendations.

<br>

# Ethical Considerations

This project acknowledges the ethical issues of invasion of privacy, as personal information of patients is used in the study. The dataset used in this project is obtained from a reputable source, the Kaggle repository, and all necessary precautions will be taken to ensure data privacy and security.

<br>
# License
This project is licensed under the **[MIT License]()**.

# Acknowledgements
This project is developed as a Master's level project and is based on the knowledge and skills acquired during the course of the Master's program in [Your University/Institution Name]. The project utilizes various machine learning techniques and is inspired by the work of researchers and developers in the field of health informatics and nutrition.

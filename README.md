Overview:
This project focuses on predicting the likelihood of Autism Spectrum Disorder (ASD) in individuals using machine learning techniques. The dataset contains responses from individuals to an Autism Spectrum Quotient (AQ) screening tool, combined with demographic and medical history information. The goal is to analyze these features and build a machine learning model to identify patterns that indicate a higher probability of ASD.

Dataset:
The dataset used in this project is publicly available and contains the following features:

Behavioral and Screening Scores:
A1_Score to A10_Score: Responses to 10 questions from the AQ screening tool. These scores measure behavioral tendencies associated with autism.
result: Outcome of the AQ test.

Demographic Information:
age: Age of the individual.
gender: Gender of the individual.
ethnicity: Ethnic background.
country_of_res: Country of residence.

Medical and Family History:
jundice: Indicates whether the individual had jaundice at birth (Yes/No).
family_history_with_autism: Indicates if there is a family history of autism (Yes/No).

Other Features:

used_app_before: Indicates if the individual used an autism screening application before.
relation: Relationship of the person who filled out the screening form.
age_desc: Age category description.

The dataset includes binary, categorical, and numerical data types, requiring preprocessing for effective model training.

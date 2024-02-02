# Data-Privacy-Toolkit---Privacy-Hub
This repository contains code and analysis for working with a toy dataset sent by a prospective client from Privacy Hub. The dataset includes variables related to physical attributes, hobbies, and a 'token' used for distinguishing patients.

## Introduction
Briefly introduce the purpose of the project and the context of the dataset. Highlight that the dataset is a toy dataset created within Privacy Hub and does not reflect real people.

## Data Tokenization
a) Variables Used for Token Creation
The token is created using a combination of variables: 'Name', 'Surname', 'Sex', 'Age', 'Height', 'Weight(kg)', 'EyeColor', 'Test Group', 'Hobbies', and 'Marital Status'. The aim is to blend these characteristics into a unique identifier for each individual.

b) Improving the Token
To enhance the token, it's crucial to ensure uniqueness, avoid sensitive information disclosure, and maintain efficiency. The token should not be overly long, achieving a balance between precision, privacy, and database storage optimization.

## Statistical Analysis
c) Average Weight for Blue-eyed Individuals aged 20-50
The average weight for a person with blue eyes aged between 20 and 50 is 72.74 kg.

d) Distribution of Values in the Height Column
The dataset shows a diverse distribution of height measurements. Factors contributing to the wide range include the small sample size and potential inconsistencies in the unit of measurement.

## Data Cleaning
d) Fixing Misalignment Issue (Row 12)
Cleaning the data is essential to address misalignment issues. Ensuring consistency in data types, handling empty rows, and implementing checks during manual data entry can improve data quality.

## Pre-processing for Analysis
e) Relationship between Sex and Favorite Hobby
Pre-processing steps involve addressing missing data, standardizing text data, and cleansing the 'Sex' and 'Hobbies' columns for accurate analysis.

## Data Sample Validity
f) Validity of Data Sample
The validity of drawing statistical conclusions from the sample depends on the representativeness and randomness of the sampling process. Consideration of biases is crucial.

## Reducing Re-identification Risk
g) Modifying Dataset for Privacy
Modifications include capping height for females at 183cm and males at 198cm. Marital status values are limited to specific categories, and values are set to 'NaN' for patients under 30.

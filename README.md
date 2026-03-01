

# Understanding Consumer Decision-Making in OTT Subscriptions

### A Behavioral Analytics Approach using Structural Equation Modeling

## Project Overview

This project analyzes the behavioral factors influencing consumer decisions to subscribe to Over-the-Top (OTT) streaming platforms. With the rapid expansion of streaming services such as Netflix, Amazon Prime Video, and Disney+ Hotstar, understanding consumer motivations behind subscription and retention has become increasingly important.

The study applies behavioral analytics and Correlation-Based Structural Equation Modeling (CB-SEM) to examine how psychological, behavioral, and economic factors influence OTT subscription intentions. Survey data is used to construct latent variables representing consumer behavior, which are then analyzed using statistical modeling techniques.

The objective is to identify the key drivers of OTT subscription behavior and provide insights that can help streaming platforms improve user engagement and retention strategies.

---

# Research Objectives

The primary objectives of this study are:

• To identify behavioral factors influencing OTT subscription decisions
• To analyze how content engagement contributes to user satisfaction and viewing habits
• To examine the role of price sensitivity, accessibility, and social influence
• To model the behavioral pathway leading to consumer subscription intention using SEM

---

# Dataset Description

The dataset used in this study consists of survey responses collected from OTT platform users.

Sample size: 212 respondents

The dataset includes:

Demographic Variables
D1 – D5 representing user background and usage characteristics

Behavioral Constructs measured using Likert-scale questions

Content Behaviour
CB1, CB2, CB3

Watch Gratification
WGA1, WGA2, WGA3, WGA4, WGA5, WGA6

Habit Generation
HG1, HG2, HG3

Accessibility
ACC1, ACC2, ACC3

Social Motivation
SM1, SM2, SM3

Cost Drivers
CD1, CD2, CD3, CD4

Consumer Intention
CI1, CI2, CI3

All constructs are measured on a Likert scale to capture the intensity of user perceptions and behavioral tendencies.

---

# Methodology

The project follows a structured behavioral analytics pipeline.

Data preprocessing
Cleaning missing values and preparing variables for statistical analysis

Exploratory analysis
Correlation matrix and descriptive statistics

Factor suitability testing
Kaiser-Meyer-Olkin (KMO) test and Bartlett’s test of sphericity

Measurement validation
Confirmatory Factor Analysis to validate latent constructs

Structural modeling
Correlation-Based Structural Equation Modeling (CB-SEM) to analyze relationships between constructs

The SEM model is implemented using Python libraries including pandas, seaborn, and semopy.

---

# Behavioral Model Framework

The conceptual behavioral model analyzed in this study follows the pathway:

Content Behaviour → Watch Gratification → Habit Generation → Consumer Intention

Additional factors influencing consumer intention include:

Accessibility
Social Motivation
Cost Drivers

This framework helps explain how content engagement leads to satisfaction, which in turn develops habitual consumption patterns that drive subscription decisions.

---

# Model Validation Results

Kaiser-Meyer-Olkin (KMO) Score: 0.835
This indicates very good sampling adequacy and strong shared variance among variables.

Bartlett’s Test of Sphericity
Chi-square: 2708.15
p-value < 0.001

These results confirm that the dataset is suitable for factor analysis and structural equation modeling.

---

# Structural Model Results

Significant relationships identified in the SEM analysis include:

Content Behaviour positively influences Watch Gratification

Watch Gratification strongly influences Habit Generation

Habit Generation significantly influences Consumer Intention

Cost Drivers significantly affect Consumer Intention

Accessibility and Social Motivation showed weaker or statistically insignificant direct effects on consumer intention.

The results indicate that habit formation plays a critical role in determining long-term OTT subscription behavior.

---

# Key Behavioral Insights

Content engagement is a major driver of user satisfaction on OTT platforms.

Users who experience higher watch gratification are more likely to develop habitual viewing patterns.

Habit formation significantly increases the likelihood of continued OTT subscriptions.

Price sensitivity also influences subscription decisions, especially when consumers manage multiple streaming services.

Social influence and accessibility appear to act as supporting factors rather than primary drivers of subscription behavior.

---

# Technologies Used

Python
Pandas
NumPy
Seaborn
Matplotlib
SEMopy (Structural Equation Modeling)

---



# Applications

This research can support:

Streaming platform product strategy
Content investment decisions
Subscription pricing optimization
User engagement and retention analysis
Consumer behavior analytics research

---

# Future Scope

Future work may extend this study through:

Integration with machine learning models for prediction
Cross-platform consumer behavior comparison
Time-series analysis of viewing habits
Recommendation system impact analysis
Regional content preference modeling

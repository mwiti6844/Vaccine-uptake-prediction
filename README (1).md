
Predicting H1N1 and Seasonal Flu Vaccine Uptake


The purpose of this project is to develop a machine learning model that can accurately predict whether a person received the H1N1 or seasonal flu vaccine based on their personal information, opinions and health behaviors. The model will be based on data collected in the National 2009 H1N1 Flu Survey.



## Problem Statement

To understand the correlation between various factors and vaccine uptake, and provide valuable insights for future public health efforts to increase vaccine coverage and reduce the spread of flu-related illnesses.

## Data description

Data
The data used in this project is collected from the National 2009 H1N1 Flu Survey and contains information on the following features:
• h1n1_concern: Represents the level of concern a person has regarding the H1N1 virus.
• h1n1_knowledge: Represents a person's level of knowledge about the H1N1 virus.
• behavioral_antiviral_meds: Indicates whether a person has taken antiviral medications in response to the H1N1 virus.
• behavioral_avoidance: Indicates the extent to which a person has altered their behavior in response to the H1N1 virus.
• behavioral_face_mask: Indicates whether a person is using face masks in response to the H1N1 virus.
• behavioral_wash_hands: Indicates whether a person is washing their hands more frequently in response to the H1N1 virus.
• behavioral_large_gatherings: Indicates whether a person is avoiding large gatherings in response to the H1N1 virus.
• behavioral_outside_home: Indicates whether a person is spending less time outside their home in response to the H1N1 virus.
• behavioral_touch_face: Indicates whether a person is touching their face less frequently in response to the H1N1 virus.
• doctor_recc_h1n1: Indicates whether a person's doctor has recommended they receive the H1N1 vaccine.
• doctor_recc_seasonal: Indicates whether a person's doctor has recommended they receive the seasonal flu vaccine.
• chronic_med_condition: Indicates whether a person has a chronic medical condition.
• child_under_6_months: Indicates whether a person has a child under 6 months of age.
• health_worker: Indicates whether a person is a health worker.
• health_insurance: Indicates whether a person has health insurance.
• opinion_h1n1_vacc_effective: Represents a person's opinion on the effectiveness of the H1N1 vaccine.
• opinion_h1n1_risk: Represents a person's perception of the risk posed by the H1N1 virus.
• opinion_h1n1_sick_from_vacc: Represents a person's opinion on the risk of getting sick from the H1N1 vaccine.
• opinion_seas_vacc_effective: Represents a person's opinion on the effectiveness of the seasonal flu vaccine.
• opinion_seas_risk: Represents a person's perception of the risk posed by the seasonal flu.
• opinion_seas_sick_from_vacc: Represents a person's opinion on the risk of getting sick from the seasonal flu vaccine.
• age_group: Represents a person's age group.
• education: Represents a person's level of education.
• race: Represents a person's race.
• sex: Represents a person's gender.
• income_poverty: Represents a person's income relative to the poverty line.
• marital_status: Represents a person's marital status.
• rent_or_own: Indicates whether a person rents or owns their home.

The labels_df data frame has a shape of 26707 rows and 2 columns and includes information about whether the respondents received the H1N1 and seasonal flu vaccines, represented by the h1n1_vaccine and seasonal_vaccine columns, respectively.

## Methodology

This project focuses on a binary classification problem and the target variable is the receipt of either H1N1 or seasonal flu vaccine. The project uses ensemble methods to combine the predictions of multiple models and improve the performance of the model. The performance of the individual models, including logistic regression, decision tree, and random forest, is also compared.

## Results

The ensemble method used in this project showed improved accuracy, precision, recall, and F1 score compared to the individual models. The final accuracy was 0.8358, precision was 0.6943, recall was 0.4, and F1 score was 0.5076.

## Conclusion

In conclusion, this project successfully developed a machine learning model that can accurately predict H1N1 and seasonal flu vaccine uptake based on personal information, opinions and health behaviors. The model provides valuable insights for future public health efforts to increase vaccine coverage and reduce the spread of flu-related illnesses.

## Future Work

Further improvement can be made to the model by incorporating additional data and features. The model can also be tested on more diverse and larger datasets to confirm its performance and applicability in other populations.
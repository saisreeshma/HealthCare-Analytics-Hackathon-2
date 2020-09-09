# HealthCare-Analytics-Hackathon-2
This project accurately predicts the Length of Stay for each patient on case by case basis.

Recent Covid-19 Pandemic has raised alarms over one of the most overlooked area to focus: Healthcare Management. While healthcare management has various use cases for using data science, patient length of stay is one critical parameter to observe and predict if one wants to improve the efficiency of the healthcare management in a hospital. 

This parameter helps hospitals to identify patients of high LOS risk (patients who will stay longer) at the time of admission. Once identified, patients with high LOS risk can have their treatment plan optimized to miminize LOS and lower the chance of staff/visitor infection. Also, prior knowledge of LOS can aid in logistics such as room and bed allocation planning.

The task is to accurately predict the Length of Stay for each patient on case by case basis so that the Hospitals can use this information for optimal resource allocation and better functioning. The length of stay is divided into 11 different classes ranging from 0-10 days to more than 100 days.

The evaluation metric for this hackathon is 100*Accuracy Score.

### Methodology
- Concatenated the train and test dataframes.
- Label Encoded the categorical variables.
- Filled the null values with a constant.
- Performed aggregations on multiple columns.
- Developed three models using CatBoostClassifier, LightGBM and XGBoost.
- Used a Voting Algorithm to finalise prediction

### Final Accuracy Score is: 0.43
### Rank in Hackathon: 44

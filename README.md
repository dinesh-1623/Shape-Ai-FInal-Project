
# Prediction of Birth Weight

This project was carried out using Logistic Regression, Random Forest classifier to predict weather newborn child will be normal birth weight or low birth weight

## Importing Libraries

- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikitlearn](https://scikit-learn.org/stable/)
- [Missingno]()
- [Statsmodels.api](https://www.statsmodels.org/stable/index.html)

## Data Exploration

Following investigation has been done:

    1. How many newborns weight is below 2.5 Kg(Low Birth Weight) and above 2.5(Normal Birth Weight) in the dataset 
    2. Is fever, Asthma and Anemia during pregnency is common and does it have any impact on newborn's weight ??
    3. Relationship between mother's age and Low Birth Weight.
    4. Fundal Height for LBW and NBW

  
## Used Models

- Logistic Regression
- Random Forest
## Visualization
![lbw_nbw_compare](https://user-images.githubusercontent.com/57408209/133417499-8bfb6424-3e94-4a2d-acd2-b0ec70d8713c.png)
![fever_asthma](https://user-images.githubusercontent.com/57408209/133417534-d9af1197-66ab-4a2a-8243-80a15ec573e9.png)
![anemia_percent](https://user-images.githubusercontent.com/57408209/133417628-34be916f-dca3-4078-858a-57ad1ee02afe.png)

![fundal_height](https://user-images.githubusercontent.com/57408209/133417562-862dde3e-ba3d-4f69-9329-346125fde50f.png)
![mother_age](https://user-images.githubusercontent.com/57408209/133417670-12ce2d22-0eac-4967-9667-498f7af11f52.png)

## Model Summary

<img width="381" alt="model_summary" src="https://user-images.githubusercontent.com/57408209/133418001-71722623-65c6-45f3-b494-0ff691f520ba.PNG">

## Logistic Regression 
(<img width="414" alt="lr_t_accuracy" src="https://user-images.githubusercontent.com/57408209/133418203-0b7fff87-8e5a-404c-886f-4d5277c28858.PNG">)

<img width="355" alt="lr_classification_report" src="https://user-images.githubusercontent.com/57408209/133418214-3992b444-d767-4c84-8e55-6444141a418f.PNG">

## Confusion Matrix for Logistic Regression
![lr_confusion](https://user-images.githubusercontent.com/57408209/133418229-4e667455-05d4-41e7-bb3a-3fabc0deac73.png)

## Random Forest
<img width="414" alt="rf_t_accuracy" src="https://user-images.githubusercontent.com/57408209/133418835-dc049046-032d-46cf-816a-2444316d5a45.PNG">
<img width="341" alt="rf_classification_report" src="https://user-images.githubusercontent.com/57408209/133418847-80880e98-cadd-4553-ac24-2461136cff1e.PNG">

## Confusion Matrix for Random Forest

![confusion](https://user-images.githubusercontent.com/57408209/133420202-13881675-7f52-4cff-85f0-54edc33402bc.png)

## ROC Curve
![roc](https://user-images.githubusercontent.com/57408209/133418890-4b548c23-3864-479f-8c69-67756c834b79.png)



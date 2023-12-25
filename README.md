# Crop Prediction System using Machine Learning

This project, developed by a team of four individuals, aims to predict crop yields based on various features using machine learning. We employ five different algorithms to train the model and predict crop yields.

## Team Members

- [Tanvi kamanuri](https://www.linkedin.com/in/kamanuri-tanvi-35759a25b/)
- [Yagna valkini](https://www.linkedin.com/in/yagna-valkini-suryadevara-b1929b217/)
- [Sandeep Rajanla](https://www.linkedin.com/in/rvssm-sandeep/)
- [Karthik](https://www.linkedin.com/in/karthik117a635/)

## Dataset

The dataset used for this project contains the following features:

- State_Name: Name of the state
- Crop_Type: Type of crop
- Crop: Specific crop name
- N, P, K: Soil nutrient levels (in kg/ha)
- pH: Soil pH level
- Rainfall: Annual rainfall (in mm)
- Temperature: Average temperature (in degrees Celsius)
- Area_in_hectares: Cultivation area in hectares
- Production_in_tons: Crop production in tons
- Yield_ton_per_hec: Yield per hectare (target variable)

## Algorithms

We have implemented the following five machine learning algorithms:

1. Random Forest
2. Support Vector Machine (SVM)
3. Decision Tree
4. Gradient Boosting
5. K-Nearest Neighbors (KNN)

Explore the Jupyter notebook `Crop_Prediction.ipynb` for data analysis and model training.

## Results

The results of each algorithm can be found in the Jupyter notebook `Crop_Prediction.ipynb` file.

### Training Results
|Algorithm |	Desicion Tree Classifier |	Random Forest Classifier |	KNN |	SVM |	XGB |
| --------- | ------------------------ | -------------------------- | --- | --- | --- |
|train_accuracy|	99.998748|	99.998748|	10.462074|	97.717798|	99.372801|
|train_precision|	99.998748|	99.998748|	1.756034|	97.853954|	99.3849|
train_recall|	99.998748|	99.998748|	10.462074|	97.717798|	99.372801|
train_f1|	99.998748|	99.998748|	2.9996|	97.756293|	99.37602|

### Testing Results 
| Algorithm |	Desicion Tree Classifier |	Random Forest Classifier	| KNN |	SVM	| XGB |
| --------- | ------------------------ | -------------------------- | --- | --- | --- |
test_accuracy |	98.452679 |	98.908363 |	98.242364 |	97.651477 |	98.863295 |
test_precision |	98.45159 |	98.918539 |	98.264676 |	97.834533 |	98.875949 |
test_recall |	98.452679 |	98.908363 |	98.242364 |	97.651477 |	98.863295 |
test_f1 |	98.451839 |	98.911897 |	98.2457 |	97.698144 |	98.867799 |

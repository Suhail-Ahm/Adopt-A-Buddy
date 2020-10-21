# HackerEarth Machine Learning challenge: Adopt a buddy

### PROBLEM OVERVIEW

It is a multi-class classification problem. It is a supervised learning problem in which our task is to train our model with labeled dataset and predict the two target attributes:
1. breed_category(Breed category of the pet)
2. pet_category(Category of the pet target variable)

[For Further Reading](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-pet-adoption/?utm_source=challenges-modern&utm_campaign=participated-challenges&utm_medium=right-panel)

### DATASET

|SNo. | Column Name | Description |
|------------|------------|-------------|
|1	    | pet_id	       | Unique Pet Id |
|2	    | issue_date	   | Date on which the pet was issued to the shelter |
|3	    | listing_date	 | Date when the pet arrived at the shelter |
|4	    | condition	     | Condition of the pet |
|5	    | color_type	   | Color of the pet |
|6	    | length(m)	     | Length of the pet (in meter) |
|7	    | height(cm)	   | Height of the pet (in centimeter) |
|8	    | X1, X2	         | Anonymous columns |
|9	    | *breed_category* |	Breed category of the pet (**target variable**) |
|10	    | *pet_category*	 | Category of the pet (**target variable**) |

### METHADOLOGY

1. *Exploratory Data Analysis:*

1. *Data Preprocessing:*
	- Imputing Values
	- Feature Extraction

1. *Algorithms Implemented:*
	- XGBoost
	- CatBoost

1. *Hyperparameter tuning:*
	- BayesianSearch CV

1. *Prediction and Evaluation Metric:*

![alt tag](https://user-images.githubusercontent.com/32522581/96785611-ad06d000-140c-11eb-94b4-f5d490fae88f.PNG)

1. *Result:* 

![alt tag](https://user-images.githubusercontent.com/32522581/96786632-32d74b00-140e-11eb-9152-e4d10537c719.png)

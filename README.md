**Project Background:** 

The topic in question for this project is readmission prediction for diabetes patients. Readmission rates are around 26 percet in the United States and happen because of a variety of reasons – this project aims to explore why these readmissions occur by attempting to apply Machine Learning techniques to the issue. 


This is a multivariate classification problem using several supervised learning algorithms such as LogisticRegression, SVC, RandomForest, KNearestNeighbors, and GradientBoosting. 

The dataset contains over 100,000 observations and variables on medications, medical history, and demographic information. 

The target is “readmitted”, with 3 unique values: <30 day readmission, >30 day readmission, and no readmission. 


**Prerequisites:** 

Python 3.11.4 

Package imports:

- Pandas
- Numpy
- matplotlib.pyplot
- seaborn
- sklearn.preprocessing
- StandardScaler
- OneHotEncoder
- OrdinalEncoder
- LabelEncoder
- MinMaxScaler
- sklearn.impute
- SimpleImputer
- sklearn.compose
- ColumnTransformer
- sklearn.pipeline
- Pipeline
- sklearn.model\_selection
- train\_test\_split
- RepeatedKFold
- GridSearchCV
- cross\_val\_score
- KFold
- sklearn.metrics
- f1\_score
- classification\_report
- confusion\_matrix
- make\_scorer
- sklearn.linear\_model
- LogisticRegression
- sklearn.ensemble
- RandomForestClassifier
- GradientBoostingClassifier
- sklearn.dummy
- DummyClassifier
- sklearn.svm
- SVC
- sklearn.neighbors
- KNeighborsClassifier
- Pickle
- shap

**Author:** 

Aysha Allahverdiyeva, Brown University DSI Institute 

**License:** 

This project is made available under the MIT License. This is a permissive and flexible open-source license that places almost no restrictions on how you can use this software. It allows you to use, modify, distribute, and sublicense the code. 

The MIT License also has important stipulations:

Attribution: Any use of the original or modified code must include the original copyright notice and license.

No Liability: The code is provided "as is", without warranty of any kind. As a user, you assume all risks that may arise. 

**Environment:** 

To use Anaconda/MiniConda to set up the appropriate environment in running this code: 

conda create -n myenv python=3.11.4 

- To create environment 

conda activate myenv

- To activate environment 

conda deactivate

- To deactive 

Pull from the linked repository to access code within desired environment. 

Link: https://github.com/aysha-alv/Predicting-Diabetes-Readmission/tree/main

Git clone [copied link to repo]

- To copy above repository, the link is accessible through the green code button in the repository on Github 

**some files (eg. X_train_prep, model outputs) are too big to be exported to the repo - when running the code on a local machine, these files will appear in the respected folders (results/data)** 

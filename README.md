# Disease-prediction-using-Machine-Learning
Implementation of various machine learning algorithms to predict the disease from symptoms given by user

### Sourcerer [![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/images/0)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/links/0)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/images/1)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/links/1)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/images/2)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/links/2)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/images/3)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/links/3)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/images/4)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/links/4)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/images/5)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/links/5)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/images/6)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/links/6)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/images/7)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Disease-prediction-using-Machine-Learning/links/7)
Disease Prediction from Symptoms
This project explores the use of machine learning algorithms to predict diseases from symptoms.

Algorithms Explored
The following algorithms have been explored in code:

Naive Bayes
Decision Tree
Random Forest
Gradient Boosting
Dataset
Source-1
The dataset for this problem used with the main.py script is downloaded from here:

https://www.kaggle.com/kaushil268/disease-prediction-using-machine-learning
This dataset has 133 total columns, 132 of them being symptoms experienced by patiend and last column in prognosis for the same.

Source-2
The dataset for this problem used with the Jupyter notebook is downloaded from here:

https://impact.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html
This dataset has 3 columns:

Disease  | Count of Disease Occurrence | Symptom
You can either copy paste the whole table from here to an excel sheet or scrape it out using Beautifulsoup.

Directory Structure
|_ dataset/
         |_ training_data.csv
         |_ test_data.csv

|_ saved_model/
         |_ [ pre-trained models ]

|_ main.py [ code for laoding kaggle dataset, training & saving the model]

|_ notebook/
         |_ dataset/
                  |_ raw_data.xlsx [Columbia dataset for notebook]
         |_ Disease-Prediction-from-Symptoms-checkpoint.ipynb [ IPython Notebook for loading Columbia dataset, training model and Inference ]
Usage
Please make sure to install all dependencies before running the demo, using the following:

pip install -r requirements.txt
Interactive Demo
For running an interactive demo or sharing it with others, please run demo.py using Jupyter Notebook or Jupyter Lab.

jupyter notebook demo.ipynb
Standalone Demo
For running the inference on test set or on custom inputs, you can also use the infr.py file as follows:

python infer.py
NOTE: This project is for demo purposes only. For any symptoms/disease, please refer to a Doctor.

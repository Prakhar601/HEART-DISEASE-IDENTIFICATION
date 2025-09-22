    # HEART-DISEASE-IDENTIFICATION

    Overview:

    This project builds predictive machine learning models 
    to identify heart disease in patients using clinical and demographic data. 
    It walks through data loading, cleaning, exploratory analysis, model training, evaluation, 
    and provides insights for future improvements.

    Table of Contents:

	•	Project Overview
	•	Dataset Description
	•	Exploratory Data Analysis
	•	Model Building & Evaluation
	•	Key Results
	•	Installation & Usage
	•	Contributing
	•	License

    Project Structure:-

    heart-disease-project/
    ├── Heart-disease-project.ipynb   # Jupyter notebook with all steps
    ├── README.md                     # Project documentation
    ├── data/                         # Dataset folder (if included)
    ├── outputs/                      # Plots, results, or model files
    └── requirements.txt              # Python dependencies
    
    Dataset Description:-

    The dataset has 303 samples and 14 attributes:
                              
                 
    | Feature         Description                                         |
    |--------------|------------------------------------------------------|
    | age          | Age in years                                         |
    |sex           | Sex (0 = female, 1 = male)                           |
    | cp           | Chest pain type (4 values)                            |
    | trestbps     | Resting blood pressure (mm Hg)                        |
    | chol         | Serum cholesterol (mg/dl)                             |
    | fbs          | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)|
    | restecg      | Resting ECG results (0,1,2)                           |
    | thalach      | Maximum heart rate achieved                            |
    | exang        | Exercise-induced angina (1 = yes; 0 = no)             |
    | oldpeak      | ST depression induced by exercise                      |
    | slope        | Slope of the peak exercise ST segment                 |
    | ca           | Number of major vessels (0-3) colored by fluoroscopy  |
    | thal         | 3 = normal; 6 = fixed defect; 7 = reversible defect  |
    | target       | 0 = No disease; 1 = Disease present    
     
    No missing values are present, and features include integers and floats.

    Exploratory Data Analysis:-

	•	Class Distribution: Roughly balanced target variable.
	•	Feature Exploration: Summary statistics and correlation matrix generated.
	•	Visualisation: Distribution plots, bar charts, and heatmaps to examine relationships with the target.

    Model Building & Evaluation:-

    Three machine learning classifiers were built and compared:
    
    | Model                | Test Accuracy |
    |----------------------|---------------|
    | Logistic Regression  | 88.5%         |
    | K-Nearest Neighbors  | 68.9%         |
    | Random Forest        | 83.6%         |

    •	Best Model: Logistic Regression.
	•	Hyperparameter tuning, feature engineering, and additional model suggestions are included in the notebook.


    Key Results:-

	•	Logistic Regression achieved 88.5% test accuracy.
	•	No significant class imbalance observed.
	•	Most important features: cp, thalach, exang.
    
    Installation & Usage:-
    Prerequisites:-

	•	Python 3.x
	•	Jupyter Notebook
	•	Packages: numpy, pandas, matplotlib, seaborn, scikit-learn

    Steps:-

	1.	Clone the repository:
        git clone https://github.com/username/heart-disease-project.git
        cd heart-disease-project
    
    2. Install dependencies:-
       pip install -r requirements.txt

    3. Open the notebook:
       jupyter notebook Heart-disease-project.ipynb

    Follow the notebook sections to explore EDA, train models, and analyse results. 
    
    Contributing:-
    
    Contributions are welcome! Suggestions for improving models, data cleaning, or visualizations can be submitted via pull requests.

    License:-

    This project is open-source and available under the MIT License.

# CSE422 Artificial Intelligence Project
 
## FIFA22 Position Prediction

**Introduction:**
In the realm of FIFA22 Position Prediction, the efficacy of machine learning models heavily relies on their training methodologies and underlying algorithms. This repository contains a comprehensive approach to predict player positions within the FIFA 22 game using various machine learning models and techniques.

**Motivation:**
The objective of the FIFA22 Position Prediction study is to augment gameplay by precisely projecting player locations, refining team composition, and investigating machine learning methodologies. Solving difficulties and restrictions in predictive modeling brought on by the dynamic nature of player movements also advances sports analytics. This project aims to stimulate research and innovation in machine learning, sports analytics, and gaming technologies by fusing domain experience with state-of-the-art approaches.

**Data Description:**
The dataset used in this project consists of 31 features, including player attributes such as age, nationality, overall rating, potential, club, preferred foot, and various skill ratings. The label, "Best_Position," indicates the player's best position based on their attributes, with 15 unique classes converted to 8 for multi-class classification.

**Data Pre-Processing:**
The data preprocessing steps involved in this project include handling null values, creating new features such as 'Contract_duration,' removing duplicates, dropping unnecessary columns, converting currency columns to numeric values, encoding categorical variables, and resampling using SMOTE to balance class distribution.

**Model Training and Visualization:**
Several machine learning models were trained and evaluated for position prediction:
- Decision Tree
- Random Forest
- XGBoost
- Logistic Regression
- Naive Bayes Classifier

Each model's concept, mathematical formulation, and evaluation metrics are provided, along with visualizations where applicable.

**Repository Structure:**
- **data:** Contains the dataset used in the project.
- **notebooks:** Jupyter notebooks detailing the data preprocessing, model training, and evaluation steps.
- **scripts:** Python scripts for data preprocessing, model training, and visualization.
- **models:** Serialized trained models for deployment or further analysis.
- **visualizations:** Visualizations generated during the analysis, such as confusion matrices, feature importance plots, etc.
- **README.md:** Detailed information about the project, including an overview, setup instructions, and usage guidelines.


**Contributing:**
Contributions to this project are welcome! If you have any ideas for improvement, new features, or bug fixes, feel free to submit a pull request.

**License:**
This project is licensed under the MIT License. See the LICENSE file for more details.

**Acknowledgements:**
Special thanks to the original data source on Kaggle and the contributors whose work has been referenced in this project.

**Contact:**
For any inquiries or feedback, please contact [email@example.com].

**References:**
- Kaggle Dataset: [FIFA 22 Complete Player Dataset](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset)
- Kaggle Notebook Reference: [FIFA22 Position Prediction](https://www.kaggle.com/code/aidinkiany/fifa22-position-prediction)

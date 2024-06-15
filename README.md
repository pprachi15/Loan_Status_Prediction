# 📊 Loan Status Prediction 📊
This project automates a finance company's loan approval using machine learning. It predicts eligibility based on online application data, including qualifications, marital status, education, work history, and credit score, improving the efficiency and accuracy of loan decisions.


### Dependencies

- `numpy`: Library for array operations in Python.
- `pandas`: Data manipulation and analysis library.
- `seaborn`: Statistical data visualization library.
- `sklearn`: Library for machine learning models and tools.
  - `model_selection`: Contains tools for model selection and evaluation.
  - `svm`: Support Vector Machine model.
  - `preprocessing`: Tools for data preprocessing, including `StandardScaler`.
  - `metrics`: Evaluation metrics such as `accuracy_score`.
 
<img src="https://github.com/pprachi15/introduction/assets/116032314/650fefe9-040d-4264-9199-339819740bb0" width="80" height="80" />      <!-- Python -->
<img src="https://github.com/pprachi15/introduction/assets/116032314/d5b9b8d2-f64d-4d44-a3ca-b86639a80ab6" width="90" height="90" />        <!-- NumPy -->
<img src="https://github.com/pprachi15/recommendation-app/assets/116032314/6f017939-05fa-4a54-86fa-ab11d39b03a9" width="80" height="80" />        <!-- Seaborn -->
<img src="https://github.com/pprachi15/introduction/assets/116032314/d1ebfe9a-1371-4c59-8088-dbef9e8a3d17" width="90" height="90" />        <!-- Pandas -->
<img src="https://github.com/pprachi15/introduction/assets/116032314/0966de8a-4ee7-4539-87a3-b80197160a75" width="80" height="80" />      <!-- Jupyter -->
<img src="https://github.com/pprachi15/introduction/assets/116032314/7b46ae33-acdf-4e06-8e26-e530da1f9133" width="70" height="70" />        <!-- VS Code -->

### Project Structure

- **Data Collection and Processing**:
  - Loads dataset from CSV file using `pandas`.
  - Performs initial exploration using `head()`, `shape`, and `describe()` functions.
  - Handles missing data by dropping rows with missing values.
  - Encodes categorical variables (`Loan_Status`, `Dependents`, `Married`, `Gender`, `Self_Employed`, `Property_Area`, `Education`) into numerical values.
  - Visualizes data relationships using `seaborn`'s `countplot`.

- **Model Training**:
  - Splits data into training and test sets using `train_test_split`.
  - Initializes and trains a Support Vector Machine (SVM) model (`svm.SVC`) with a linear kernel.

- **Model Evaluation**:
  - Evaluates model accuracy on both training and test datasets using `accuracy_score`.

- **Prediction**:
  - Demonstrates making predictions with new data using the trained SVM model.
  - Applies `StandardScaler` for scaling input data to match the model's training data.

## Highlights
<img width="589" alt="education_visual" src="https://github.com/pprachi15/recommendation-app/assets/116032314/a4c04b13-ac50-40e0-bbc5-fd5bf9a13f65">
<img width="589" alt="married_visual" src="https://github.com/pprachi15/recommendation-app/assets/116032314/b2640c75-6713-4618-8235-3226b7638207">
<img width="589" alt="gender_visual" src="https://github.com/pprachi15/recommendation-app/assets/116032314/ccd68236-dd01-43f9-a23d-b4cd60c49fd1">
<img width="589", height = "450" alt="prediction" src="https://github.com/pprachi15/recommendation-app/assets/116032314/56642829-4bb3-47f6-9f7a-fff504f92e1b">


## Usage

To run the project:
1. Clone the repository.
2. Ensure dependencies are installed (`numpy`, `pandas`, `seaborn`).
3. Run the main script or Jupyter notebook to execute the project code.
4. Follow the code comments and output to understand each step of the project.

## Contributing

Contributions to improve the project are welcome. Fork the repository and submit a pull request with your proposed changes.

👩🏻‍💻 Happy Coding 👩🏻‍💻

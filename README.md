
# Loan Eligibility Prediction Model

The Loan Eligibility Prediction project employs machine learning algorithms to assess an applicant's likelihood of loan approval by analyzing factors such as gender, marital status, education, income, loan amount, and credit history. The model is trained on a dataset of 614 loan applications, achieving an accuracy of 80% in predicting loan approvals. 

## Badges


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)

![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
## Data Preprocessing

Data preprocessing steps include:

    1. Handling Missing Values

    2. Encoding Categorical Variables: 

    3. Feature Scaling


## Model Architecture

The model is built using Keras with TensorFlow as the backend. The architecture includes:

    Input Layer: Accepts preprocessed features.
    Hidden Layers: Two dense layers with ReLU activation functions.
    Output Layer: A single neuron with a sigmoid activation function to predict the probability of loan approval.
## Training and Evaluation

The dataset is split into training and testing sets in an 80:20 ratio. The model is compiled with binary cross-entropy loss and optimized using the Adam optimizer. Performance metrics include accuracy, precision, recall, and the F1-score.
## Results

The model achieves an accuracy of 80% on the test set, indicating reliable performance in predicting loan eligibility.
## Usage

To use the model:

**1. Clone the Repository:**

```bash
git clone https://github.com/yourusername/loan-eligibility-prediction.git
```
**2. Install Dependencies:**

```bash
pip install -r requirements.txt
```

**3. Run the Prediction Script:**

```bash
python predict.py
```

---

# 📱 SPAM SMS Detection
 git overview
![Spam Detection](https://via.placeholder.com/800x200.png?text=Spam+SMS+Detection)
git overview 2
## Overview
This project aims to build a machine learning model that can classify SMS messages as spam or legitimate (ham). We use techniques like TF-IDF for text vectorization and classifiers such as Naive Bayes, Logistic Regression, and Support Vector Machines (SVM).

## Features
- Text vectorization using TF-IDF
- Multiple classification models: Naive Bayes, Logistic Regression, and SVM
- Detailed performance evaluation with classification reports and confusion matrices
- Easy-to-follow Jupyter Notebook for step-by-step understanding

## 🚀 Installation

1. ## Clone the repository:
    ```bash
    git clone https://github.com/yourusername/spam-sms-detection.git
    cd spam-sms-detection
    ```

2. ## Create a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. ## Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## 📊 Dataset
The dataset used in this project is downloaded from Kaggle and includes SMS messages labeled as spam or ham. Place the dataset file (`spam.csv`) in the `data/` directory.

## 🛠 Usage

1. ## Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. ## Open the notebook:
    Open the `spam_sms_detection.ipynb` notebook in your browser.

3. ## Follow the steps:
    - Importing Libraries
    - Defining Paths and Checking Files**
    - Loading and Preprocessing the Dataset
    - Splitting the Data
    - Vectorizing the Text Data**
    - Training and Evaluating Models**
    - Comparing Model Performance

4. **Run each cell to execute the code and observe the outputs.**

## 📈 Model Performance
We evaluate the performance of three different classifiers: Naive Bayes, Logistic Regression, and SVM. The best-performing model can be chosen for deployment based on accuracy, precision, recall, and F1-score.

## 🤝 Acknowledgments
- Dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Libraries: pandas, scikit-learn, matplotlib, seaborn

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding! 😊 If you find this project useful, please give it a ⭐ on GitHub.

### Duplicate Question Pair Detection

This project focuses on identifying duplicate question pairs on platforms like Quora using Natural Language Processing (NLP) and Machine Learning (ML) techniques. The goal is to accurately predict whether two questions have the same underlying meaning, which can help in reducing redundancy and improving user experience.

***

### Features & Methodology

The project employs a robust feature engineering approach and leverages various machine learning models to solve this binary classification problem.

* **Feature Engineering:**
    * **Token-Based Features:** Analysis of word tokens to understand the structure and content of the questions.
    * **Length-Based Features:** Comparison of question lengths, including word and character counts.
    * **Fuzzy Features:** Utilizes string matching algorithms like **Fuzzy-Wuzzy** to calculate the similarity between question pairs.
    * **TF-IDF Vectorization:** Transforms the text data into numerical vectors to represent the importance of words in the questions.

* **Models:** The project compares and evaluates the performance of several machine learning classifiers, including:
    * Logistic Regression
    * Decision Tree
    * Random Forest
    * XGBoost

***

### Installation

To run this project, you need to set up a Python environment and install the required libraries.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/sohans1092004/duplicate-question-pairs.git](https://github.com/sohans1092004/duplicate-question-pairs.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd duplicate-question-pairs
    ```

3.  **Install the necessary packages:**
    ```bash
    pip install -r requirements.txt
    ```

***

### Dataset

The model is trained on a dataset of question pairs from **Quora**, which can be obtained from the **Kaggle Quora Competition Website**. The dataset includes a binary label (`is_duplicate`) indicating if a question pair has the same meaning. Due to its size, the dataset is not included in the repository and must be downloaded separately.

***

### Project Structure

The project is typically structured with Jupyter Notebooks that guide you through the entire process, from data analysis to model building and evaluation.

* `EDA.ipynb`: Performs exploratory data analysis to understand the dataset.
* `Feature_Engineering.ipynb`: Creates and extracts new features from the raw text data.
* `Model_Training.ipynb`: Implements and evaluates the machine learning models.

***

### License

This project is open-sourced under the **MIT License**.

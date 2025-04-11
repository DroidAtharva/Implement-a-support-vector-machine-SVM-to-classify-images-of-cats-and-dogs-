# Task 03: Cats vs Dogs Classification with SVM

## Description
This project implements a **Support Vector Machine (SVM)** to classify images of **cats** and **dogs**. The goal is to build a robust image classification model using the Kaggle dataset.

## Dataset
- **Dataset Name**: Dogs vs Cats
- **Source**: [Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data)
- The dataset contains labeled images of cats and dogs.

## Requirements
- Python 3.x
- Libraries:
  - tensorflow
  - numpy
  - pandas
  - matplotlib
  - sklearn

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cats-vs-dogs-svm.git
   cd cats-vs-dogs-svm
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset from [Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data) and organize the images into `train/` and `test/` directories.
4. Run the script:
   ```bash
   python svm_classifier.py
   ```
5. View the results, including accuracy and predictions on test images.

## Output
- Classification of images into "cat" or "dog".
- Evaluation metrics such as accuracy and confusion matrix.

## License
This project is licensed under the MIT License.

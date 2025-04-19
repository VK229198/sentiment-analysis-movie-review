# Sentiment Analysis using Logistic Regression

## Project Structure

| File | Description |
|:-----|:------------|
| `IML_CP3_script.py` | Full pipeline for data preprocessing, feature extraction, model training, and evaluation. |

## Dataset

- Input: `Test.csv`
- Format: Text reviews with associated sentiment labels.

## Setup Instructions

1. Install required libraries:
    ```bash
    pip install pandas numpy scikit-learn nltk beautifulsoup4 matplotlib seaborn wordcloud spacy textblob
    ```

2. Download NLTK resources:
    ```python
    import nltk
    nltk.download('stopwords')
    nltk.download('punkt')
    nltk.download('wordnet')
    ```

3. Place `Test.csv` in the working directory.

## Running the Pipeline

```bash
python IML_CP3_script.py

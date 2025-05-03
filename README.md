# Fake News Detection Mini Project

This project aims to show that NLP fake news detectors while having impressive performance on unseen data from the same dataset where the train data comes from, tend to not generalize well on other datasets.
The experiments conducted in this project are heavily inspired than those described in the article from Hoy, Nathaniel & Koulouri, Theodora:  (2022). Exploring the Generalisability of Fake News Detection Models. 5731-5740. 10.1109/BigData55660.2022.10020583.

## Data Setup

1.  **Create a `data` directory** in the root of the project if it doesn't exist.
2.  **Download the datasets as ZIP and unzip the files:**
    *   ISOT Fake News Dataset: [Download Link](https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset/data)
        *   Place `Fake.csv` and `True.csv` directly inside the `data` directory.
    *   Fake or Real News Dataset: [Download Link](https://www.kaggle.com/datasets/jillanisofttech/fake-or-real-news)
        *   Place `fake_or_real_news.csv` directly inside the `data` directory.

3.  **Expected `data` directory structure:**

    ```
    mini_projet_nlp/
    ├── data/
    │   ├── Fake.csv
    │   ├── True.csv
    │   └── fake_or_real_news.csv
    ├── nlp_mini_fake_news_detection.ipynb
    ├── requirements.txt
    └── README.md
    ```

## Running the Notebook

Ensure you have installed the required packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

Then, you can run the `nlp_mini_fake_news_detection.ipynb` notebook.

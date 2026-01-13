# 📊 Dataset Information: Email Spam Classification

The model in this repository is trained and evaluated using the **Email Spam Classification Dataset** hosted on Kaggle.

## 🔗 Official Source
* **Dataset Link:** [Email Spam Classification Dataset CSV](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv)
* **Format:** CSV file (`emails.csv`)

## 📝 Description
This dataset contains 5,172 rows, each representing an email. The emails have been pre-processed into a word-count matrix.

### Key Features:
* **Email No.:** Unique identifier for each email.
* **Word Columns:** 3,000 columns representing the 3,000 most common words found in the emails. Each cell contains the count of that specific word in the email.
* **Prediction (Target):** * `0`: The email is **NOT SPAM** (Legitimate).
    * `1`: The email is **SPAM**.

## ⚖️ Usage Note
To run the Jupyter Notebook in this repository:
1.  Download the `emails.csv` from the Kaggle link above.
2.  Place the file in the `/data` folder of this project.
3.  Ensure the file name matches the path used in the notebook (usually `data/emails.csv`).

---
*Acknowledgment: Dataset provided by user [Balaka Biswas](https://www.kaggle.com/balaka18) on Kaggle.*

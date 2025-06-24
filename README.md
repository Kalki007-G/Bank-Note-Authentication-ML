# 🏦 Bank Note Authentication Using K-Means Clustering

This project implements an unsupervised machine learning approach to authenticate bank notes using **K-Means Clustering** based on features extracted from genuine and forged bank notes.

---

## 📂 Project Structure
- `BankNoteAuthentication_KMeans.ipynb` : Jupyter notebook containing the complete clustering pipeline.
- `data_banknote_authentication.csv` : Dataset used for model building and evaluation.

---

## 🚀 Features
- Data Preprocessing
- Unsupervised Clustering with K-Means Algorithm
- Elbow Method for Optimal Number of Clusters
- Data Visualization with Cluster Plotting
- Comparison of Clustering Results with Actual Labels (if available)

---

## 🔧 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset
**Dataset:** [UCI Machine Learning Repository - Bank Note Authentication Dataset](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)

**Attributes:**
- Variance of Wavelet Transformed image
- Skewness of Wavelet Transformed image
- Curtosis of image
- Entropy of image

---

## 📚 How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/bank-note-authentication.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

---

## 🧮 Evaluation
- K-Means is unsupervised but can be **compared to actual labels** to evaluate clustering performance using:
    - Accuracy (optional)
    - Confusion Matrix (optional)
    - Visualization of Cluster Separation

---

## ✅ Result
The K-Means model groups the data into clusters representing **genuine** and **forged** bank notes based on their features without using labeled data.

---

## 🤝 Contributions
Contributions are welcome. Feel free to fork the repository and submit pull requests.

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

---

## ✨ Acknowledgements
- Dataset provided by the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)

# Ronit10 - Data Analysis Notebook

This project contains a Jupyter Notebook (`ronit10.ipynb`) for data analysis and visualization. It demonstrates data preprocessing, exploratory data analysis (EDA), and visualization techniques using popular Python libraries.

## 🚀 Features

- Data loading and inspection
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data visualization using libraries like `matplotlib`, `seaborn`, etc.
- Insights derived from the dataset

## 📁 File Structure

```
📦ronit10-project
 ┣ 📜ronit10.ipynb
 ┗ 📜README.md
```

## 🛠️ Requirements

Install the following Python libraries before running the notebook:

```bash
pip install pandas matplotlib seaborn jupyter
```

Or use the `requirements.txt` if provided:

```bash
pip install -r requirements.txt
```

## 🔧 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `ronit10.ipynb` and run the cells.

## 📊 Screenshots / Output

--- Evaluating Ensemble Model ---

--- Individual Model Test Performance ---
Evaluating ResNet18_NoAttention_1:

ResNet18_NoAttention_1 Test Loss: 0.2878 | Test Acc: 91.00%
ResNet18_NoAttention_1 Test Precision: 0.9101 | Test Recall: 0.9100 | Test F1-Score: 0.9100

Evaluating ResNet18_Attention_1:

ResNet18_Attention_1 Test Loss: 0.3054 | Test Acc: 91.44%
ResNet18_Attention_1 Test Precision: 0.9144 | Test Recall: 0.9144 | Test F1-Score: 0.9143

Evaluating ResNet18_NoAttention_2:

ResNet18_NoAttention_2 Test Loss: 0.2847 | Test Acc: 91.11%
ResNet18_NoAttention_2 Test Precision: 0.9110 | Test Recall: 0.9111 | Test F1-Score: 0.9110

Evaluating ResNet18_Attention_2:

ResNet18_Attention_2 Test Loss: 0.2964 | Test Acc: 91.22%
ResNet18_Attention_2 Test Precision: 0.9121 | Test Recall: 0.9122 | Test F1-Score: 0.9121


--- Ensemble Model Test Performance ---

Ensemble_Model Test Loss: 0.2375 | Test Acc: 92.49%
Ensemble_Model Test Precision: 0.9248 | Test Recall: 0.9249 | Test F1-Score: 0.9248




--- Final Results ---

Ensemble Model Accuracy: 92.49%

Ensemble Model Precision: 0.9248

Ensemble Model Recall: 0.9249

Ensemble Model F1-Score: 0.9248


## 🙋‍♂️ Author

**Ronit** – [GitHub](https://github.com/yourusername)

---

Feel free to fork, star, and contribute! 🌟

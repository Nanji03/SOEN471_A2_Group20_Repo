# **SOEN471_A2_Group20_Repo**

## **How to Run the Project**

### **Option 1: Google Colab (Recommended)**

1. Open the notebook in **Google Colab**
2. Click **“Run all”** to execute all cells
3. Outputs (recommendations, metrics, and plots) will be displayed automatically

---

### **Option 2: Local Execution (Jupyter Notebook)**

1. Download the `.ipynb` file
2. Install the required dependencies (see below)
3. Open the notebook using Jupyter
4. Run all cells sequentially

---

## **Dependencies**

Install the following Python libraries before running:

```
pandas  
numpy  
scikit-learn  
mlxtend  
matplotlib  
seaborn  
```

(Warning handling uses Python’s built-in `warnings` module — no installation needed.)

---

## **Project Structure**

* `*.ipynb` → Main notebook containing:

  * Data preprocessing
  * User-Based Collaborative Filtering implementation
  * Association Rule Mining (Apriori)
  * Evaluation metrics and analysis
  * Data visualizations and Recommendation approaches visualization

* Dataset:

  * Loaded within the notebook, _ecommerce_user_data.csv_ and _product_details.csv_ (ensure correct file path if running locally)

---

## **Outputs**

Running the notebook will generate:

* Cleaned and organized user item matrix
* Grouped and aggregated purchase behaviours
* User similarity matrix
* Top-N product recommendations per user for User Based Collaborative Filtering
* Evaluation metrics (Precision@K, Recall@K, MAP, Coverage, Diversity) for User Based Collaborative Filtering
* Association rules (support, confidence, lift)
* Generated rules applying Apriori
* Top 10 most frequent itemsets based on support
* Heatmaps of user similarity and user similarity ordered by groups 
* Top-N product recommendations per user group
* Tabular summary for report/dashboard use
* Frequent itemsets bar chart

---

## **Notes**

* Ensure all cells are run **in order** to avoid dependency errors
* Results may slightly vary due to randomness in train-test split



# E-commerce-Customer-Segmentation
Implemented K-Means clustering for marketing strategy optimization.
# 🛒 E-Commerce Customer Segmentation (RFM + K-Means)

## 📌 Overview
This project implements **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering** to segment e-commerce customers based on their purchasing behavior.  
The goal is to enable **targeted marketing strategies** by identifying distinct customer groups such as VIPs, regular buyers, and lost customers.

---

## 🎯 Problem Statement
E-commerce businesses have thousands of customers, each with different spending habits and loyalty levels.  
The challenge is:
- How can we group customers meaningfully?
- How can we create personalized marketing campaigns for each group?

---

## 💡 Solution
We:
1. Processed transaction data and calculated **RFM metrics** for each customer.
2. Scaled these features for better clustering performance.
3. Applied **K-Means clustering** to group customers into distinct segments.
4. Profiled each segment to create **actionable marketing recommendations**.

---

## 📊 RFM Metrics Explained
- **Recency (R)** → Days since the last purchase.  
  Lower value = more recent purchase.
- **Frequency (F)** → Total number of purchases.  
  Higher value = more loyal.
- **Monetary (M)** → Total money spent.  
  Higher value = more valuable.

---

## 🛠️ Tech Stack
- **Language**: Python 3.x
- **Libraries**:
  - pandas, numpy → Data processing
  - matplotlib, seaborn → Visualization
  - scikit-learn → K-Means clustering, scaling
- **Dataset**: [Online Retail Dataset (UCI ML Repository)](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

---

## 📂 Project Structure
E-Commerce-Customer-Segmentation/
│
├── data/
│ └── online_retail.csv # Dataset file
│
├── notebooks/
│ └── EDA_and_Clustering.ipynb # Jupyter notebook with full workflow
│
├── src/
│ └── rfm_analysis.py # Functions for RFM calculation
│ └── clustering.py # K-Means and evaluation
│
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## 🚀 How to Run the Project
1. **Clone this repository**
```bash
git clone https://github.com/your_username/Ecommerce-Customer-Segmentation.git
cd Ecommerce-Customer-Segmentation
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run Jupyter Notebook

bash
Copy
Edit
jupyter notebook notebooks/EDA_and_Clustering.ipynb
Explore results

Cluster visualizations

RFM distribution plots

Marketing recommendations

📈 Results
Segmented customers into 4 groups:

Cluster 0: VIP Customers (High F, High M, Low R)

Cluster 1: Lost Customers (Low F, Low M, High R)

Cluster 2: Regular Buyers (Medium F, Medium M)

Cluster 3: Bargain Hunters (Low M, High F, Medium R)

Created actionable marketing plans for each group.

🎯 Business Impact
Helps marketing teams target campaigns effectively.

Improves customer retention and engagement.

Increases ROI by focusing resources on high-value customers.

📚 Future Improvements
Implement DBSCAN or Hierarchical Clustering for comparison.

Add a Streamlit dashboard for interactive segmentation.

Enable real-time clustering for incoming customer data.

👤 Author
Mr.RatanBajaj
📧 ratankumar4937@gmail.com
🔗 LinkedIn | Portfolio

# 🚀 Reduced medical store inventory loss by 20–30% using data analysis and ML 💊

## 🚨 Problem
Medical stores often face:
- Loss due to expired medicines (observed: ~16–17%)
- Overstocking and understocking
- Poor demand prediction

This leads to direct financial losses and inefficient capital usage.

---

## 💡 Solution
This project builds a data-driven system to:
- Analyze inventory inefficiencies
- Identify high-value and low-performing medicines
- Predict future sales using ML (XGBoost)
- Optimize stock decisions

---

## 📊 Key Insights



### 📉 Inventory Loss
<img width="800" height="226" alt="Expired Stock Distribution" src="https://github.com/user-attachments/assets/458a352d-b490-4378-bc4a-7461ba4dbb91" />

- ~16% of expired stock was never sold  
👉 Direct financial loss

---

### ⚖️ Stock Imbalance
<img width="800" height="432" alt="Top Overstocked and Understocked Medicines" src="https://github.com/user-attachments/assets/21815a85-21f5-4a5d-9c57-a841061135f6" />


- Overstocked items: Capital blocked  
- Understocked items: Lost sales  

---

### 📈 Sales Forecasting
<img width="800" height="532" alt="Daily Sales Trends Actual vs Predicted" src="https://github.com/user-attachments/assets/319cf2e1-5781-411a-8ce6-7165fabcefc9" />


- ML model achieved **R² ≈ 0.79**

  ---

## 📸 Visual Insights

### ABC Analysis
<img width="800" height="401" alt="ABC Analysis Inventory Value Contribution by Medicine" src="https://github.com/user-attachments/assets/b17bae44-8219-4b95-ad1b-28956a220453" />


### Customer Segmentation (RFM)
<img width="800" height="487" alt="Medicine Recency vs Frequency (Bubble Size = Monetary Value)" src="https://github.com/user-attachments/assets/51bbcd0d-2301-431f-99a3-540d65acc783" />


### Efficiency Analysis (DEA)
<img width="800" height="476" alt="Top 20 Efficient Medicines (DEA Score)" src="https://github.com/user-attachments/assets/cc7e12da-a147-4a70-9296-94d62667efa4" />



### 💊 High-Value Products
  - Small number of medicines drive most revenue (ABC)
  - Few products dominate performance (RFM + DEA)

  👉 Focus on "sales drivers"

---

### 📈 Sales Prediction
  - ML model achieved **R² ≈ 0.79**
  - Reliable demand forecasting

  👉 Enables proactive decision-making

---

## 📈 Business Impact

This system can help:
- Reduce expiry losses by **20–30%**
- Increase revenue through better stock planning
- Improve capital efficiency
- Prevent stockouts of high-demand medicines

---

## 🛠 Tech Stack
- Python 3.8+
- Pandas (Data manipulation)
- NumPy (Numerical computing)
- Scikit-learn (ML algorithms)
- XGBoost (Advanced ML model)
- Matplotlib & Seaborn (Visualization)
- Jupyter Notebook

---

## 📁 Project Structure
```
medical-store-inventory-optimization-ml/
├── data/                          # Input datasets
│   ├── inventory_data.csv
│   └── sales_data.csv
├── notebooks/
│   └── final_client_ml.ipynb      # Main analysis notebook
├── outputs/
│   ├── charts/                    # Generated visualizations
│   └── reports/                   # Analysis reports
├── README.md                      # Project documentation
├── requirements.txt               # Python dependencies
└── LICENSE                        # MIT License
```

---

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip or conda package manager

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/medical-store-inventory-optimization-ml.git
cd medical-store-inventory-optimization-ml
```

### Step 2: Create Virtual Environment
```bash
# Using venv
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Or using conda
conda create -n medical-inventory python=3.8
conda activate medical-inventory
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

### Option 1: Jupyter Notebook (Interactive)
```bash
jupyter notebook notebooks/final_client_ml.ipynb
```
Then open the notebook and run cells sequentially.

### Option 2: Command Line (Batch Processing)
```bash
python -m jupyter nbconvert --to notebook --execute notebooks/final_client_ml.ipynb
```

---



---

## 💼 What I Can Do for Your Business

I help medical stores:
- Reduce losses from expired stock
- Identify high-demand medicines
- Optimize inventory planning
- Forecast future sales

---

## ⭐ Key Takeaway
A data-driven approach can significantly improve profitability and reduce waste in medical stores.

---

## 📧 Contact & Support
For questions, collaborations, or deployment inquiries:
- **Email**: ashishpay2@gmail.com
- **GitHub Issues**: Open an issue for bugs or feature requests

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing
Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📦 Sample Business Recommendation

Based on this analysis:

- Reduce stock of slow-moving medicines (e.g., Metol XL)
- Increase stock of high-demand items (e.g., Paracetamol)
- Implement FEFO to reduce expiry loss
- Use demand prediction for weekly stock planning

👉 Expected Result:
- 20–30% reduction in losses
- Better cash flow

 ---

## 🔮 Future Improvements
- [ ] Real-time inventory monitoring dashboard
- [ ] API deployment for predictions
- [ ] Integration with pharmacy management systems
- [ ] Mobile app for stock alerts
- [ ] Demand forecasting for seasonal variations

---

**Last Updated**: Feb 2026 
**Maintained by**: ashish kumar sharma

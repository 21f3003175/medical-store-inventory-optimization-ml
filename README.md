# Medical Store Sales & Inventory Optimization using Machine Learning 💊

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
- ~16% of expired stock was never sold  
👉 Direct financial loss

---

### ⚖️ Stock Imbalance
- Overstocked items: Capital blocked  
- Understocked items: Lost sales  

👉 Need balanced inventory strategy

---

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

## 🔮 Future Improvements
- [ ] Real-time inventory monitoring dashboard
- [ ] API deployment for predictions
- [ ] Integration with pharmacy management systems
- [ ] Mobile app for stock alerts
- [ ] Demand forecasting for seasonal variations

---

**Last Updated**: April 2024  
**Maintained by**: Your Name

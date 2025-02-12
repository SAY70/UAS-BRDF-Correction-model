# 🌿 mRTLS Model Performance Analysis

![Project Banner](https://your-image-link.com/banner.png)  

## 📖 About the Project
The **mRTLS model** is an advanced approach for analyzing land-cover reflectance using root mean square error (RMSE) as a performance metric. This project compares the mRTLS model with the traditional RTLS model across different land-cover types (vegetation, soil, and water) and varying geometric conditions.

## 🚀 Features
- 📊 **Comparative analysis** between mRTLS and RTLS models
- 📈 **RMSE calculations and visualizations** for different land-cover types
- 🔄 **Time-based performance evaluation** (10:30 AM, 1 PM, 4:15 PM)
- 🖥️ **Python-based implementation** with Matplotlib for error plots

## 🛠 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mrtls-analysis.git
   cd mrtls-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Usage
Run the main script to analyze RMSE and generate visualizations:
```bash
python main.py
```

## 📂 Project Structure
```
📁 mrtls-analysis
│-- 📄 main.py            # Main script for analysis
│-- 📂 data               # Dataset files
│-- 📂 plots              # Generated RMSE visualizations
│-- 📄 requirements.txt   # Required Python packages
│-- 📄 README.md          # Project documentation
```

## 📜 Results Summary
- The **mRTLS model** performs better than the RTLS model at **optimal geometry (1 PM)**.
- At **non-optimal times (10:30 AM, 4:15 PM)**:
  - **Vegetation & Soil**: Significant RMSE increase (reduced accuracy).
  - **Water**: Slight RMSE increase, indicating less sensitivity to geometric variations.

## 📸 Visualizations
![RMSE Comparison](https://your-image-link.com/rmse_comparison.png)  

## 🤝 Contributing
We welcome contributions! Feel free to submit pull requests or open issues.



---
🌟 **Star this repository** if you find it useful!


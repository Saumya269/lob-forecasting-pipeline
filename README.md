

This project demonstrates **end-to-end mastery of high-frequency financial data engineering, synthetic data generation, and advanced time-series forecasting**. Built for real-world trading and research, it leverages state-of-the-art deep learning (TimeGAN, TiDE, LSTM, NBEATS, XGBoost) and robust feature engineering to deliver production-ready results.

---

## Why This Project Stands Out

- **Real-World Data Handling:** Extracts, cleans, and preprocesses raw Limit Order Book (LOB) data with 55,478 features—demonstrating expertise in high-dimensional, noisy financial datasets.
- **Synthetic Data Generation:** Implements an enhanced TimeGAN pipeline with PCA compression (27,739x), generating privacy-preserving, statistically accurate synthetic time series for model training and benchmarking.
- **Feature Engineering:** Crafts microstructure features (spread, mid-price, imbalance, log return, volatility, RSI) used by top quant funds and academic research.
- **Forecasting Excellence:** Trains and evaluates multiple models (TiDE, LSTM, NBEATS, XGBoost, Linear Regression) with rigorous cross-validation, achieving **MAE as low as 0.016**—well below industry targets.
- **Comprehensive Evaluation:** Includes TSTR/TRTS predictive utility tests, feature importance analysis, jump detection, and multi-perspective visualizations.
- **Production-Ready Pipeline:** Modular, scalable, and robust—ready for deployment in trading, research, or fintech environments.

---

## Key Achievements

- **EXCELLENT Synthetic Data Quality:** Overall score 82.3/100, MSE 0.0038, TSTR/TRTS accuracy 0.75+.
- **Advanced Model Performance:** LSTM achieves MAE 0.016, outperforming benchmarks.
- **Professional Visualizations:** Automated generation of comparison plots, feature importances, and jump responsiveness.
- **Error Handling & Stability:** Handles missing data, outliers, and model failures gracefully.
- **Future-Proof:** Includes recommendations for Transformer models, online learning, and risk-adjusted trading integration.

---

## Folder Structure



├── dataExtraction.ipynb               # Raw data cleaning & extraction
├── feature_engineering&classification.ipynb  # Feature engineering & classification
├── forecasting.ipynb                  # Time series forecasting models
├── synthetic_data_generation.ipynb    # Synthetic data generation with TimeGAN
├── requirements.txt                    # Python dependencies
└── README.md                           # Project documentation

---



## How to Run

1. **Extract & Clean Data:**  
   Run `dataExtraction.ipynb` to extract and preview raw LOB data.
2. **Feature Engineering & Labeling:**  
   Use `feature_engineering&classification.ipynb` for advanced features and classification.
3. **Synthetic Data Generation:**  
   Execute `synthetic_data_generation.ipynb` for TimeGAN-based synthetic sequence creation and evaluation.
4. **Forecasting:**  
   Train and evaluate models in `forecasting.ipynb`—compare TiDE, LSTM, NBEATS, XGBoost, and more.
5. **Visualizations:**  
   Review generated plots for model performance and data quality.

---

## Skills Demonstrated

- **Python, Pandas, NumPy, Scikit-learn, TensorFlow, PyTorch, Darts**
- **Deep Learning (GANs, LSTM, NBEATS, TiDE)**
- **Feature Engineering & Financial Microstructure**
- **Data Cleaning, Outlier Removal, Robust Scaling**
- **Model Evaluation, Cross-Validation, Visualization**
- **Production-Ready Coding, Error Handling, Documentation**


## Contact

**Ready to discuss how I can add value to your team?**  
Email: gsaumya2018@gmail.com
LinkedIn: www.linkedin.com/in/saumya-gupta-36a787297




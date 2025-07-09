# nifty-volatility-analysis
# 📈 Nifty Volatility Analysis with Clustering

This project analyzes high-frequency Nifty index data (sampled every 15 seconds) to extract and cluster volatility patterns using Python.

## 🔧 Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (KMeans)
- Google Colab

## 📊 Key Steps
- Processed 7GB dataset with memory-efficient sampling
- Selected 3 representative rows per day
- Extracted VIX (Volatility Index) data
- Applied KMeans clustering (5 clusters)
- Visualized day-wise volatility behavior

## 📁 File Structure
- `internship1.pynb`: Full code
- `vix_3rows_per_day.feather`: Sample of the original data


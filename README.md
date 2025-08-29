
# Crop Yield & Pesticides Analysis

[![View Interactive Report](https://img.shields.io/badge/View-Interactive%20Report-blue?style=for-the-badge)](https://fahmidhasann.github.io/CropYield_Pesticides_Analysis/CropYield_Pesticides_Analysis%20(Interactive%20Charts).html)
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> Comprehensive exploratory data analysis examining the relationship between global pesticide usage and crop yields across 165+ countries (1990-2016)

## 🌾 Overview

This project analyzes global agricultural data to understand patterns and correlations between pesticide application and crop productivity. The analysis features interactive visualizations and focuses on identifying trends across different countries and crop types, with special attention to Bangladesh and leading agricultural nations.

### Key Insights
- **Geographic Coverage**: 165 countries for pesticide data, 101 countries for yield data
- **Temporal Scope**: 1990-2016 (pesticides), 1990-2013 (crop yields)
- **Crop Analysis**: 8 major crops including rice, wheat, maize, soybeans, and others
- **Environmental Factors**: Rainfall, temperature, and pesticide usage correlations

## 📊 Datasets

| Dataset | Description | Records | Timeframe |
|---------|-------------|---------|-----------|
| `pesticides.csv` | Annual pesticide usage by country (tonnes of active ingredients) | ~4,350 | 1990-2016 |
| `yield_df.csv` | Crop yields with environmental factors (hg/ha, rainfall, temperature) | ~28,240 | 1990-2013 |

## 🚀 Quick Start

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook/JupyterLab

### Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/fahmidhasann/CropYield_Pesticides_Analysis.git
   cd CropYield_Pesticides_Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the analysis**
   ```bash
   jupyter notebook "CropYield_Pesticides_Analysis (Interactive Charts).ipynb"
   ```

4. **Run all cells** to generate interactive visualizations

## 📈 Analysis Highlights

### 🔍 Key Research Questions
1. Which countries lead in pesticide usage globally?
2. How has pesticide application evolved over time?
3. What correlations exist between pesticide use and crop yields?
4. How does Bangladesh compare to global agricultural patterns?
5. Which crops show the strongest yield-pesticide relationships?

### 📊 Visualization Features
- **Interactive Charts**: Built with Plotly for dynamic exploration
- **Correlation Analysis**: Statistical relationships between variables
- **Time Series**: Trends and patterns over multiple decades
- **Comparative Analysis**: Country and crop-level comparisons
- **Geographic Insights**: Regional agricultural patterns

## 🛠️ Technical Stack

- **Data Processing**: `pandas`, `numpy`
- **Visualization**: `plotly`, `matplotlib`, `seaborn`
- **Statistics**: `scipy`, `statsmodels`
- **Environment**: `jupyter`, `ipywidgets`
- **Export**: `kaleido` for static image generation

## 📁 Project Structure

```
├── CropYield_Pesticides_Analysis (Interactive Charts).ipynb  # Main analysis notebook
├── CropYield_Pesticides_Analysis (Interactive Charts).html   # Interactive report
├── pesticides.csv                                            # Pesticide usage data
├── yield_df.csv                                              # Crop yield data
├── requirements.txt                                          # Python dependencies
├── LICENSE                                                   # MIT License
└── README.md                                                 # Project documentation
```

## 🎯 Research Focus Areas

- **Global Leaders**: Identification of top pesticide-using countries
- **Bangladesh Analysis**: Detailed examination of local agricultural patterns
- **Crop-Specific Studies**: Individual analysis of rice, wheat, maize, and other major crops
- **Environmental Correlations**: Impact of rainfall and temperature on yields
- **Temporal Trends**: Evolution of agricultural practices over 25+ years

## 📝 Citation

If you use this analysis in your research, please cite:

```
Hasan, F. (2024). Crop Yield & Pesticides Analysis: Global Agricultural Data Exploration (1990-2016). 
GitHub Repository: https://github.com/fahmidhasann/CropYield_Pesticides_Analysis
```

## 👨‍🎓 Author

**Fahmid Hasan**  
*B.Sc.Ag (Hons), Bangladesh Agricultural University, Mymensingh*  
📧 [taohid.2102010@bau.edu.bd](mailto:taohid.2102010@bau.edu.bd)

[![GitHub](https://img.shields.io/badge/GitHub-fahmidhasann-black?style=flat&logo=github)](https://github.com/fahmidhasann)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <strong>🌱 Contributing to Agricultural Data Science 🌱</strong>
</div>

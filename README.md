# Interactive Dimensionality Reduction & Visualization Tool

A plug-and-play Jupyter Notebook for exploratory data analysis (EDA), dimensionality reduction, and visualization. Upload datasets, apply PCA/SVD/NMF, explore data interactively, and export results for further analysis.

***

## 📌 Features

- **Upload any CSV or Excel dataset**
- **Choose decomposition method**: PCA, SVD, NMF
- **Select number of components** interactively
- **Visualize**: 2D/3D scatter plots, feature heatmaps, explained variance curves
- **Download transformed data** for ML pipelines
- **Easy, interactive controls** (dropdowns, sliders, buttons)

***

## 🌍 Real-World Applications

- **Machine Learning Feature Engineering**
- **Noise Reduction & Feature Selection**
- **Recommender Systems & Matrix Factorization**
- **Text Mining & NLP (topic modeling)**
- **Genomics & Bioinformatics Data Exploration**

***

## 🚀 Roadmap & Improvement Ideas

- Clustering overlays (KMeans, DBSCAN)
- Feature importance loading plots
- Support for categorical data (One-Hot Encoding)
- Add non-linear methods: t-SNE, UMAP
- Time-series dimensionality reduction
- Convert notebook to Streamlit/Dash web app
- Automated summary reports & insights

***

## 🛠️ Installation

1. Clone the repo:
    ```bash
    git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
    cd YOUR_REPO_NAME
    ```
2. Install requirements:
    ```bash
    pip install numpy pandas matplotlib seaborn scikit-learn ipywidgets
    ```
    - For Excel import:
    ```
    pip install openpyxl
    ```
3. (Optional) Enable Jupyter widgets:
    ```bash
    pip install ipywidgets
    jupyter nbextension enable --py widgetsnbextension
    ```

***

## ⚡ Usage

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open `Interactive_DimRed_EDA.ipynb`.
3. **Upload your data**. Use interactive widgets to select decomposition and visualization options.
4. **Analyze, visualize, and download** transformed data.

***

## 📝 Updating on GitHub

1. After each notebook edit, save your changes.
2. Run:
    ```bash
    git add Interactive_DimRed_EDA.ipynb
    git commit -m "Describe your update"
    git push origin main
    ```

***

## 👨💻 Contributing

- Submit PRs for new features, bug fixes, improvements.
- Open issues for feedback, suggestions, and enhancement ideas.

***

## 📄 License

MIT License. Feel free to use and modify for research, teaching, or commercial applications.

***

## 🙏 Acknowledgments

Inspired by open-source dimensionality reduction libraries and EDA best practices.

***

**Ready to explore your data? Dive into dimensionality reduction and visualization now!**

Sources

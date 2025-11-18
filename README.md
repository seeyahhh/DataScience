# Data Science Subject Repository

This repository serves as a collection of core projects, analyses, and code related to the Data Science subject. It includes implementations of various machine learning models, data visualization examples, and foundational statistical analyses.

## Structure

The repository is organized into the following directories to keep different types of content easily accessible:

* **`data/`**: Stores datasets used for analysis (small files, or a placeholder for instructions on where to download larger files).
* **`notebooks/`**: Contains Jupyter notebooks (`.ipynb` files) where exploratory data analysis (EDA), model training, and visualization are performed.
* **`outputs/`**: For final presentations, PDF reports, or markdown summaries of key project findings.

---

## Key Project Areas

### 1. Data Visualization (`/notebooks/viz/`)

This section focuses on using libraries like **Matplotlib**, **Seaborn**, and **Plotly** to create informative and aesthetically pleasing visualizations.

* **Goals:**
    * Exploratory Data Analysis (EDA) visualizations (histograms, scatter plots, box plots).
    * Time-series plots and geospatial data representation.
    * Interactive dashboards (if applicable).

### 2. Regression Analysis (`/notebooks/regression/`)

Implementations and case studies involving various regression techniques, primarily using **scikit-learn** and **statsmodels**.

* **Examples:**
    * **Linear Regression:** Basic implementation and assumptions check.
    * **Ridge/Lasso Regression:** Regularization techniques to prevent overfitting.
    * **Logistic Regression:** Classification using a linear model.

### 3. Machine Learning Models (`/notebooks/models/`)

This folder contains notebooks dedicated to training and evaluating different supervised and unsupervised machine learning models.

* **Supervised Learning:**
    * Decision Trees and Random Forests.
    * Support Vector Machines (SVM).
    * K-Nearest Neighbors (KNN).
* **Unsupervised Learning:**
    * K-Means Clustering.
    * Dimensionality Reduction (PCA).

## Installation and Setup Script

### 1. Clone the repository
``` bash
git clone https://github.com/seeyahhh/DataScience.git
cd DataScience
```
### 2. Create a virtual environment
**Windows**
``` bash
python -m venv .venv
.\.venv\Scripts\activate
```

**macOS/Linux**
``` bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Upgrade pip
```
pip install --upgrade pip
```

### 4. Install required dependencies
**Typical requirements for this repository include:** pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, statsmodels, jupyter
``` 
pip install pandas numpy matplotlib seaborn plotly scikit-learn statsmodels jupyter
```

### 5. Optional: Install Jupyter Notebook/Lab if not included
```
pip install notebook
```
 or for JupyterLab
 ```
pip install jupyterlab
```

### 6. Launch Jupyter Notebook
 ```
jupyter notebook
```

### 7. Navigate to the notebooks folder and open desired notebook
 Example:
 * **`notebooks/viz/`**
 * **`notebooks/regression/`**
 * **`notebooks/models/`**

 ### 8. To deactivate virtual environment when done
 Windows
 ```
deactivate
```
 macOS/Linux
```
deactivate
```


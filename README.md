<h1 align="center">Applied Data Analysis & Data Science</h1>

<p align="center">
  <a href="https://pandas.pydata.org/">
    <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  </a>
  <a href="https://numpy.org/">
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" alt="Numpy">
  </a>
  <a href="https://scikit-learn.org/">
    <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn">
  </a>
  <a href="https://matplotlib.org/">
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" alt="Matplotlib">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-darkred?style=for-the-badge" alt="License">
  </a>
</p>

<p align="center">
  <b>A comprehensive technical journey from core Python paradigms to advanced Machine Learning implementations.</b><br><br>
  <i>Showcasing production-level CRUD operations, sophisticated OOP architectures, and rigorous data science pipelines.</i>
</p>
<br>
<p align="center">
  <a href="#technical-architecture">
    <img src="https://img.shields.io/badge/Architecture-222222?style=flat" />
  </a>
  <span> ° </span>
  <a href="#project-structure">
    <img src="https://img.shields.io/badge/Structure-222222?style=flat" />
  </a>
  <span> ° </span>
  <a href="#detailed-module-specifications">
    <img src="https://img.shields.io/badge/Modules-222222?style=flat" />
  </a>
  <span> ° </span>
  <a href="#technical-specifications">
    <img src="https://img.shields.io/badge/Specs-222222?style=flat" />
  </a>
  <span> ° </span>
  <a href="#deployment--installation">
    <img src="https://img.shields.io/badge/Deploy-222222?style=flat" />
  </a>
</p>

---
<br>
<h2 align="center">Technical Architecture</h2>

The repository is structured as a progressive learning ecosystem, moving from deterministic logic to probabilistic modeling:

1.  **Fundamental Layer (W1):** Implementation of RESTful patterns and in-memory state management using Python's core data structures.
2.  **Structural Layer (W2):** Modeling complex domains using advanced Object-Oriented Programming (OOP) principles, including Mixins and Abstraction.
3.  **Engineering Layer (W3):** Leveraging the `Pandas` engine for high-performance data manipulation, normalization, and relational algebra.
4.  **Predictive Layer (W4-W5):** Deployment of supervised learning algorithms (Regression and Classification) using `Scikit-Learn` pipelines.

---
<br>
<h2 align="center">Project Structure</h2>

```
Applied-DataAnalysis-and-DataScience/
├── w1-CRUD_Operators_with_API/                # API Integration & CRUD Operations
│   ├── main.py                               # Core logic for NewsAPI interaction
│   └── API_KEY.py                            # sensitive configuration placeholder
│
├── w2-OOP/                                    # Advanced Object-Oriented Design
│   ├── 8_Mix.py                               # Complex Football Club simulation
│   └── [1-7]_Concepts.py                     # Atomic OOP demonstrations
│
├── w3-Pandas/                                 # Data Engineering & Preparation
│   ├── 1.[2-8]_Operations.py                 # Cleaning, Joins, Stats, and Visualization
│   └── 2.1_Mix.py                             # Unified data processing workflow
│
├── w4-LinearRegression/                       # Predictive Quantitative Analysis
│   ├── 1_Diabetes.ipynb                       # Health metrics regression
│   └── [2-3]_Datasets.ipynb                  # Horse-Colic and Iris studies
│
└── w5-Classification/                         # Categorical Inference Models
    ├── 1.1-Mysterious_Classification.ipynb   # Unlabeled data classification
    ├── 2.1-Mushroom_Classification.ipynb     # Biological safety prediction
    └── 3.1-IMDB_Movie_Ratings_Prediction.ipynb # Sentiment and rating analysis
```

---
<br>
<h2 align="center">Detailed Module Specifications</h2>

### 🏗️ Week 1: CRUD Operators & API Integration
This module focuses on the transition from static code to dynamic data consumption.
- **Dynamic Field Fetching:** Implements a flexible `fetch_news(*args)` function that parses JSON responses from **NewsAPI (TechCrunch source)** based on runtime-defined fields.
- **In-Memory CRUD:** A complete management system (`create`, `read`, `update`, `delete`) with automatic ID generation and state persistence during runtime.
- **Technical Rigor:** Handles nested JSON objects (e.g., `source` mappings) and provides a clean CLI interface for data orchestration.

### 🏛️ Week 2: Object-Oriented Programming (OOP)
A deep dive into building scalable software architectures.
- **The Football Management Simulation (`8_Mix.py`):** Uses multiple inheritance and mixin patterns to create a hierarchical representation of a club.
- **Encapsulation & Protection:** Implementation of private attributes (e.g., `__department_name`) with getter/setter logic to ensure data integrity.
- **Polymorphism in Action:** Method overriding across `BaseClub`, `FootballClub`, and `TechnicalTeam` to provide specialized behaviors for universal interfaces.

### 🐼 Week 3: Advanced Data Manipulation with Pandas
Demonstrates the heavy-duty data engineering required for real-world Data Science.
- **Feature Engineering:** Scripts for `Standardization` (Z-score) and `Normalization` (Min-Max) to prepare data for sensitive ML algorithms.
- **Relational Operations:** Masterful use of `Merge` and `Join` to unify disparate CSV datasets.
- **Exploratory Data Analysis (EDA):** Visualization scripts using `Seaborn` and `Matplotlib` to identify patterns, correlations, and outliers.

### 📉 Week 4: Regression Analysis
Quantitative modeling using the Scikit-Learn framework.
- **Diabetes Dataset:** predicting disease progression using multivariate linear regression.
- **Horse Colic Dataset:** Advanced handling of sparse data and missing value imputation for predictive health diagnostics.
- **Evaluation Metrics:** rigorous validation using R-squared (R²), Mean Squared Error (MSE), and residual analysis.

### 🏷️ Week 5: Classification Algorithms
Binary and multi-class categorical prediction tasks.
- **Mushroom Classification:** Determining poisonous vs. edible status using categorical feature encoding.
- **IMDB Ratings Prediction:** NLP-adjacent classification task for movie rating categories based on metadata.
- **Mysterious Dataset:** A "black box" challenge involving high-dimensional data, requiring feature importance analysis and model selection.

---
<br>
<h2 align="center">Technical Specifications</h2>

<table align="center">
  <tr>
    <th align="center">Domain</th>
    <th align="center">Technology Stack</th>
  </tr>
  <tr>
    <td align="center">Language</td>
    <td align="center">Python 3.10+</td>
  </tr>
  <tr>
    <td align="center">Data Engine</td>
    <td align="center">Pandas, NumPy</td>
  </tr>
  <tr>
    <td align="center">Visualization</td>
    <td align="center">Matplotlib, Seaborn</td>
  </tr>
  <tr>
    <td align="center">Machine Learning</td>
    <td align="center">Scikit-Learn (LR, SVM, RF, NB)</td>
  </tr>
  <tr>
    <td align="center">API Interaction</td>
    <td align="center">Requests, JSON</td>
  </tr>
</table>

---
<br>
<h2 align="center">Deployment & Installation</h2>

### 1. Repository Acquisition
```bash
git clone https://github.com/Zer0-Bug/Applied-DataAnalysis-and-DataScience.git
cd Applied-DataAnalysis-and-DataScience
```

### 2. Environment Configuration
Install the comprehensive suite of dependencies:
```bash
pip install -r requirements.txt
```

### 3. API Setup (Week 1)
To run the NewsAPI integration, you must:
1.  Obtain an API key from [newsapi.org](https://newsapi.org/).
2.  Update `w1-CRUD_Operators_with_API/API_KEY.py` with your credentials:
    ```python
    API_KEY = "your_key_here"
    ```

### 4. Exploring Notebooks (Week 4-5)
```bash
jupyter notebook
```

---
<br>
<h2 align="center">Contribution</h2>

Contributions are always appreciated. Open-source projects grow through collaboration, and any improvement—whether a bug fix, new feature, documentation update, or suggestion—is valuable.

To contribute, please follow the steps below:

1. Fork the repository.
2. Create a new branch for your change:  
   `git checkout -b feature/your-feature-name`
3. Commit your changes with a clear and descriptive message:  
   `git commit -m "Add: brief description of the change"`
4. Push your branch to your fork:  
   `git push origin feature/your-feature-name`
5. Open a Pull Request describing the changes made.

All contributions are reviewed before being merged. Please ensure that your changes follow the existing code style and include relevant documentation or tests where applicable.

---
<br>
<p align="center">
  <a href="mailto:777eerol.exe@gmail.com">
    <img src="https://cdn.simpleicons.org/gmail/D14836" width="40" alt="Email">
  </a>
  <span> × </span>
  <a href="https://www.linkedin.com/in/eerolexe/">
    <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png"
         width="40"
         alt="LinkedIn">
  </a>
</p>

---

<p align="center" style="margin-top:10px; letter-spacing:4px;">
  ∞
</p>

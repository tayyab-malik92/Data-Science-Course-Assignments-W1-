# Data-Science-

**Topic:** Pandas First-Look Protocol & Exploratory Data Analysis (EDA)  

## 📊 Dataset Profile
* **Dataset Chosen:** Netflix Movies & Shows  
* **Domain:** Entertainment / Digital Media  
* **Dimensions:** 1000+ Rows | 12 Columns  

### Why this dataset?
Streaming platforms generate massive amounts of unstructured and semi-structured metadata. Understanding categorical distributions (movies vs. TV shows), text trends (directors, cast, countries), and timeline patterns (release years vs. addition dates) offers critical business insights into digital content strategies.

---

## ⚙️ Repository Pipeline & Deliverables
This repository contains the full exploratory analysis workflow as outlined in the assignment criteria:

1. **Part B (Dataset Selection):** Picked a dataset satisfying the minimum constraint of 500 rows and 5 columns.
2. **Part C (The 7-Command First-Look Protocol):** Executed core structural audits (`.shape`, `.dtypes`, `.info()`, `.describe()`, `.isnull()`, `.value_counts()`, `.duplicated()`) with a detailed Markdown interpretation cell explaining the findings after each step.
3. **Part D (Deep Investigation):** Implemented 20+ additional EDA commands (15 from the core checklist and 5 self-explored Pandas commands including `.skew()`, `.kurt()`, `.mode()`, and memory usage audits).

---

## 🔍 Key Findings from the Data
* **Content Class Imbalance:** Feature-length "Movies" significantly outnumber episodic "TV Shows" in volume, proving that movies remain the primary library driver for the platform.
* **Modern Production Bias:** Statistical skewness and kurtosis checks on release years show that the catalog is heavily weighted toward modern titles, leaving classic or historical cinema as a small minority.
* **High Missing Metadata Density:** Essential categorical features—specifically `director` and `cast`—display high missing value rates. This indicates that dropping null rows is inefficient, and robust placeholder/imputation strategies must be deployed before any modeling.

---

## 🛠️ How to Run the Notebook
1. Clone this repository or download the `TayyabDS_W1.ipynb` file.
2. Open the file in **Google Colab** or any local Jupyter Notebook environment.
3. Run the cells sequentially to observe the outputs and corresponding data interpretations.

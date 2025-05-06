# Principles of Data Analytics

## Overview

This repository contains submissions for the module *Principles of Data Analytics*. It includes exploratory data analysis, visualizations, and insights derived from the Iris dataset using Python.

---

## Repository Contents

- `tasks.ipynb`: Jupyter Notebook performing data analysis and visualization tasks on the Iris dataset.
- `README.md`: Project documentation.
- `.gitignore`: Specifies files and directories to be ignored by Git.

---

## Dataset Information

The analysis utilizes the classic Iris dataset, which comprises 150 observations of iris flowers from three species:

- *Iris-setosa*
- *Iris-versicolor*
- *Iris-virginica*

Each observation includes four features:

- Sepal length
- Sepal width
- Petal length
- Petal width

This dataset is widely used for demonstrating statistical classification techniques and machine learning algorithms.

---

## Technologies Used

- **Python**: Programming language for data analysis.
- **Jupyter Notebook**: Interactive environment for running Python code.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization.
- **Scikit-learn**: Machine learning library.

---

## Getting Started

To run the analysis:

1. **Clone the repository**:

  ```bash
  git clone https://github.com/EderOlimpio/principles_of_data_analytics.git
  cd principles_of_data_analytics
   ```

2. **Create a virtual environment** (optional but recommended):

  ```bash
  python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install the required packages**:

  ```bash
  pip install pandas matplotlib scikit-learn jupyter
```

4. **Launch Jupyter Notebook**:

  ```bash
  jupyter notebook tasks.ipynb
```
---

## Analysis Performed

The notebook includes:

- **Data Loading**: Importing the Iris dataset.

- **Exploratory Data Analysis (EDA)**:

  - Descriptive statistics.

  - Data visualization (histograms, scatter plots).

- **Machine Learning**:

  - Implementing classification algorithms.

  - Evaluating model performance.

---

## References

- Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. Computing in Science & Engineering, 9(3), 90-95. https://doi.org/10.1109/MCSE.2007.55

- Matplotlib Developers. (n.d.). Matplotlib: Visualization with Python. Retrieved from https://matplotlib.org/

- McKinney, W. (2018). Python for Data Analysis: Data Wrangling with Pandas, NumPy, and Jupyter (2nd ed.). O'Reilly Media.

- Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., … & Duchesnay, E. (2011). Scikit-learn: Machine learning in Python. Journal of Machine Learning Research, 12, 2825-2830. Retrieved from https://scikit-learn.org/

- Fisher, R. A. (1936). The use of multiple measurements in taxonomic problems. Annals of Eugenics, 7(2), 179-188. https://doi.org/10.1111/j.1469-1809.1936.tb02137.x

---

Author: Eder Olimpio

### Detecting Outliers in Customer Purchase Behavior

This project aims to detect outliers in customer purchase behavior using the Isolation Forest algorithm. The dataset used contains features such as `Age`, `Annual Income`, `Purchase Amount`, `Purchase Frequency`, and `Customer Rating`, and the goal is to identify unusual patterns that could inform business insights.

## Prerequisites

Ensure you have the following installed before running the notebook:

* Python 3.x (preferably Python 3.8 or later)
* Jupyter Notebook (or Jupyter Lab)
* Python libraries:
    * pandas
    * numpy
    * scikit-learn
    * matplotlib
    * seaborn

## Installation Instructions
   
1. Clone this repository to your local machine:
```bash
    git clone https://github.com/chiragtiwari6842/Isolation-Forest.git
    cd Demo
```

2. Create a virtual environment (optional but recommended) to avoid conflicts with other projects:

```bash
    python -m venv env
```
3. Activate the virtual environment:

* On Windows:

```bash
    .\env\Scripts\activate
```

* On Mac/Linux:

```bash
    source env/bin/activate
```

4. Install the required dependencies:

```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
```

5. Launch the Jupyter Notebook:

6. Open the isolation_forest.ipynb file from the Jupyter interface and run the notebook cells sequentially.

## Running the Notebook

Once you've opened the notebook, follow these steps:

1. Data Preprocessing: The first few cells handle data loading, missing value imputation, and feature encoding.
2. Model Training: The Isolation Forest is applied to detect outliers.
3. Visualization: Scatter plots and other visualizations are provided to analyze the outliers.
4. Business Insights: Conclusions and analysis of the detected outliers are included.

## Dataset

Ensure you have the required dataset in place. The notebook assumes the dataset is in the same directory.

## Conclusion

This project helps identify unusual customer behavior, which can assist in refining marketing strategies, managing risks, 
or optimizing inventory.


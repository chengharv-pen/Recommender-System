# Big Data Analytics - E-Commerce Recommender System & Association Rule Mining

[Google Colab link](https://colab.research.google.com/github/chengharv-pen/Recommender-System/blob/main/project_notebook.ipynb)

## Installation & Dependencies
Ensure you have Python installed, then install the required packages:
```sh
pip install numpy pandas matplotlib jupyter scikit-learn seaborn mlxtend networkx adjustText
```

## File Structure
```
project_root/
│-- data/
│   │-- ecommerce_user_data.csv
│   │-- product_details.csv
│-- project_notebook.ipynb
│-- README.md
```

- **`data/`**: Contains raw datasets.
- **`project_notebook.ipynb`**: Jupyter notebook for processing and analyzing data.
- **`README.md`**: Setup.

## Running the Project
1. Modify the directory structure if needed. Default paths:
   ```
   ./data/ecommerce_user_data.csv
   ./data/product_details.csv
   ```
2. Open the Jupyter notebook:
   ```sh
   jupyter notebook ./project_notebook.ipynb
   ```
3. Run all cells to execute data processing and visualization.

## Notes
- If using another environment (e.g., VSCode), ensure the directory structure is correctly referenced.
- Adjust file paths accordingly when running scripts.

# Michael J Moore: Exploratory Data Analysis Project
This project demonstrates Exploratory Data Analysis (EDA) using Python, Pandas, Matplotlib, Seaborn, and Jupyter Notebooks. The initial analysis focuses on the Iris dataset, showing how to load the data, inspect its structure, and perform basic exploration.

## Workflow and Commands
Clone the repository:
git clone https://github.com/waldomac00/datafun-04-eda

cd datafun-04-notebooks

Create and activate a virtual environment:
### Windows
py -3.12 -m venv .venv
.\.venv\Scripts\activate


## Install dependencies:
python -m pip install --upgrade pip setuptools wheel
python -m pip install numpy pandas matplotlib seaborn ipywidgets jupyter ipykernel
Register the Jupyter kernel:
python -m ipykernel install --user --name datafun-04 --display-name "Python (datafun-04)"
Launch Jupyter Notebook:
jupyter notebook
Or open the project in Visual Studio Code and select the kernel named Python (datafun-04).

## Example Notebook Code
import pandas as pd
import seaborn as sns
iris_df = sns.load_dataset('iris')
print(iris_df.columns)
print(iris_df.head())

## Project Structure
datafun-04-notebooks/
├── .venv/                   # Virtual environment (excluded from GitHub)
├── notebooks/               # Jupyter notebooks
│   └── michaeljmoore-notebook.ipynb
├── README.md                # Project documentation
├── requirements.txt         # Dependencies list
└── .gitignore               # Ignored files

## Managing Dependencies
Save installed packages to requirements.txt:
python -m pip freeze > requirements.txt
Recreate the environment later with:
pip install -r requirements.txt

## Notes on README Formatting
Use Markdown syntax with headings, code blocks, and lists to make the README.md look professional. Always capitalize the file name as README.md. Follow conventions used in professional repositories: clear instructions, consistent formatting, and concise explanations.

## Next Steps
Extend the EDA with statistical summaries and advanced visualizations. Document insights inside notebooks. Apply the workflow to additional datasets for deeper analysis.

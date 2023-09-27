# datafun-06-projects

By Solomon Stevens
Github Repository: https://github.com/Stone-Snevets/datafun-06-projects
Date: September 29,2023
Focus: Perform exploratory data analysis on multiple datasets

### Create and Activate Virtual Environment in VS Code
To **CREATE** a new virtual environment

1. Open a new terminal
-> Click "View" then "Terminal" or type Ctrl+`

2. Type the following into the terminal:
```shell
python -m venv .venv
```
If that doesn't work try replacing "python" with "python3" or "py"

3. Check if a new .venv folder was created
-> If so, you have successfully created a new virtual environment

To **ACTIVATE** this virtual environment

1. In the terminal, type the following depending on your operating system:
-> For PowerShell: `.venv\Scripts\Activate`
-> For macOS/Linux:  `source .venv/bin/`

### Install Reqired Dependencies

1. Type the following in the terminal:
```shell
python -m pip install --upgrade pip ipykernel jupyterlab
python -m pip install --upgrade pandas matplotlib seaborn
python -m pip install --upgrade voila
```

-> ipykernel and jupyterlab are required to actually run a notebook
-> pandas is used for working with the data
-> matplotlib and seaborn are to create charts / graphs
-> viola makes notebooks standalone web applications

### Execute Python Files

1. Create a python kernel for the virtual environment
-> In the terminal, type the following line:
```shell
python -m ipykernel install --user --name .venv --display-name "Python (.venv)"
```
-> Again, if you are having issues with this, try "python3" or "py" instead of "python"

2. In a Python Notebook (.ipynb)
A. Select the appropriate kernel... the one we just created
B. Run the Python Notebook

-> You can clear the kernel whenever you need by clicking "Restart" at the top of the page
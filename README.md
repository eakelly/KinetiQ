# KinetiQ Tutorial

## Installation Instructions

### 1. Clone the Repository
Run the following commands to clone the repository and navigate to its directory:
```bash
git clone https://github.com/eakelly/kinetiq.git
cd kinetiq
```

### 2. Install Dependencies
Ensure you have Python 3.8 or higher installed. Install the required dependencies with:
```bash
pip install -r requirements.txt
```

### 3. Install Additional Tools
- Install Jupyter Notebook:
  ```bash
  pip install notebook
  ```
---

## Environment Setup Guide

### 1. Create a Virtual Environment (Recommended)
Run the following to create and activate a virtual environment:
```bash
python -m venv kinetiq_env
source kinetiq_env/bin/activate 
```

### 2. Verify Installation
Check if all dependencies are installed correctly:
```bash
python -m pip check
```

### 3. Launch Jupyter Notebook
Start the Jupyter Notebook server:
```bash
jupyter notebook
```
Open the latest `kinetiq_v4.ipynb` notebook in your browser.

---

## Usage Examples and Demonstrations

### 1. Open the Notebook
Open the `kinetiq_v4.ipynb` notebook in Jupyter.

### 2. Run Setup Cells
- Navigate to the `Setup` and `Experiment Functions` sections.
- Run all the cells in these sections to initialize the environment and load the required functions.

### 3. Run Experiments
- Locate the `Experiments` section in the notebook.
- Run the experiments using the `run_api_calls()` function. This function executes API calls and generates results files.

### 4. Perform Comparisons Without API Calls
- Use the `compare_query_parameters()` function to evaluate and compare results without making additional API calls. This function reads the results from the files created during a `run_api_calls()` execution.

### 5. Generate Results
- Navigate to the `Results` section of the notebook.
- Run the cells to generate and visualize the results.

---

## Troubleshooting Guide

### 1. Environment Issues
- **Problem**: Package installation errors.  
  **Solution**: Ensure your virtual environment is activated and run:
  ```bash
  pip install -r requirements.txt
  ```

- **Problem**: Version conflicts with Python or dependencies.  
  **Solution**: Ensure Python version is 3.8 or higher. If conflicts persist, create a new virtual environment.

### 2. Notebook Errors
- **Problem**: `ModuleNotFoundError` when importing libraries.  
  **Solution**: Run the following to reinstall missing packages:
  ```bash
  pip install <missing_package_name>
  ```

### 3. API Call Failures
- **Problem**: Errors during `run_api_calls()`.  
  **Solution**:
  - Verify your internet connection.
  - Check API credentials and configuration files.
  - Ensure the API endpoint is correct by reviewing the error message.

- **Problem**: No results are generated.  
  **Solution**: Ensure all setup cells have been run and the API server is accessible.

### 4. Result Generation Issues
- **Problem**: Missing or incomplete result files during `compare_query_parameters()`.  
  **Solution**: Rerun the `run_api_calls()` function to regenerate the necessary files.
---

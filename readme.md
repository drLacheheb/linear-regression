# Concrete Data Analysis Project

## Overview

This project focuses on analyzing a dataset containing concrete data. The analysis is performed using Python and various data science libraries such as Pandas, NumPy, and more. The project demonstrates data loading, preprocessing, and basic analysis techniques.

## Project Structure

- `main.py`: The main script that loads and processes the concrete dataset.
- `requirements.txt`: A file specifying the Python dependencies for the project.
- `README.md`: Project documentation with an overview and setup instructions.
- `Concrete_Data.csv`: The CSV file containing the concrete dataset (converted from `.xls`).

## Installation

To get started with this project, follow these steps:

1. Create and activate a virtual environment:

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

2. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Make sure that the `Concrete_Data.csv` file is in the project directory.
2. Run the main script:

    ```sh
    python main.py
    ```

## Requirements

- Python 3.12 or higher
- Required Python packages (specified in `requirements.txt`)

## Dependencies

- `pandas==1.5.3`
- `xlrd>=2.0.1`
- `numpy==1.23.4`
- `scipy==1.9.3`
- `matplotlib==3.6.1`
- `seaborn==0.12.1`
- `scikit-learn==1.2.2`
- `jupyter==1.0.0`
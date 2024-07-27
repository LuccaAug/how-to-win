# How to Win: a Data Exploration of Winning Matches from La Liga Matches Using FP-Growth

## Description

This project involves analyzing data from La Liga, the top professional football division in Spain, to identify patterns in winning matches. 
By applying the FP-growth algorithm, a popular method for frequent pattern mining, the project aims to uncover insights into factors that contribute to successful outcomes for teams. 
The analysis includes data exploration and visualization to provide a comprehensive view of the patterns and trends within the dataset.

## Installation

### Option 1: Using Poetry

To set up the project, follow these steps:

1. **Install Poetry**

   If Poetry is not already installed, you can install it using the following command:

   ```sh
   curl -sSL https://install.python-poetry.org | python3 -
   ```

   For more installation options, refer to the [Poetry documentation](https://python-poetry.org/docs/#installation).

2. **Install Project Dependencies**

   Navigate to the project directory (if not already there) and install the dependencies:

   ```sh
   poetry install
   ```

   This command will create a virtual environment and install all required packages as specified in the `pyproject.toml` file.

3. **Activate the Virtual Environment**

   To activate the virtual environment created by Poetry, use:

   ```sh
   poetry shell
   ```

   This step is necessary to ensure that the installed packages are available for use.

### Option 2: Using pip

1. **Create a Virtual Environment**

   Create a virtual environment in the project directory:

   ```sh
   python -m venv venv
   ```

2. **Activate the Virtual Environment**

   - On Windows:

     ```sh
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```sh
     source venv/bin/activate
     ```

3. **Install Project Dependencies**

   Install the dependencies using pip:

   ```sh
   pip install numpy matplotlib pyfpgrowth
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.






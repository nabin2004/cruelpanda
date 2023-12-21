# CruelPanda

CruelPanda is your relentless companion in the world of data, delivering swift and potent data analysis with a touch of audacity. With a fierce focus on tabular data and simplified regex functionalities, CruelPanda empowers you to conquer datasets with unmatched agility. Experience data analysis on a new level – where the wild meets wisdom! 📈✨

## Directory Structure

```plaintext
cruelpanda/
├── cruelpanda/
│   ├── __init__.py
│   ├── core.py
│   ├── regex.py
├── tests/
│   ├── __init__.py
│   ├── test_core.py
│   ├── test_regex.py
├── docs/
│   ├── conf.py
│   ├── index.rst
├── setup.py
├── README.md
├── requirements.txt
```

## Core Functionalities

### `core.py` - Tabular Data Analysis:

The `core.py` file contains functions tailored for rapid analysis of tabular data. Here are some examples:

- **`summarize_data(dataframe)`:** Provides summary statistics of the input DataFrame.
- **`clean_data(dataframe)`:** Performs basic cleaning operations on the DataFrame.
- **`visualize_data(dataframe)`:** Creates basic visualizations for the data.

## Regex Support

### `regex.py` - Simplified Regex Support:

In the `regex.py` file, you'll find functions for simplified regex operations on dataframes:

- **`filter_by_regex(dataframe, column, pattern)`:** Filters DataFrame rows based on a regex pattern in a specified column.
- **`extract_by_regex(dataframe, column, pattern)`:** Extracts data based on a regex pattern in a specified column.

## Testing and Documentation

- **`tests/`**: This directory contains test files (`test_core.py` and `test_regex.py`) to ensure that your functions work as expected.

- **`docs/`**: Consider using tools like Sphinx to generate documentation for your package. Proper documentation is essential for users to understand how to use your package effectively.

## Packaging and Versioning

- **`setup.py`**: Set up package metadata and dependencies.

- **`README.md`**: This file! Include essential information about your package, installation instructions, and examples.

- **`requirements.txt`**: List the required dependencies for your package.

This directory structure is designed to keep your code organized, separating core functionalities from regex-related operations. As your package evolves, you can easily expand it by adding new modules, functionalities, and support for different data formats or analysis techniques.


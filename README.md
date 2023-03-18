# Randomly Generated DataFrame with Hover Styling
This repository contains a simple Python script that generates a random Pandas DataFrame and applies a hover styling to it. The script uses the ```pandas``` and ```numpy``` libraries to generate a 5x3 DataFrame with values randomly generated from a standard normal distribution.

The script also modifies the styling of the DataFrame using the ```.style``` attribute of the DataFrame object. Specifically, it applies a yellow background color to the rows of the DataFrame when they are hovered over with the mouse. This is achieved using the ```.style.set_table_styles()``` method with a CSS selector and property.

# Usage
To use this script, simply clone the repository and run the ```random_dataframe.py``` file using Python. The script will generate a DataFrame and display it with hover styling in your console or IDE. You can modify the script to generate different sizes or types of DataFrames, or experiment with different CSS styles using the ```.style``` attribute of the DataFrame object.

# Requirements
This script requires Python 3.x and the ```pandas``` and ```numpy``` libraries to be installed. You can install these libraries using ```pip```, the Python package manager.

```
pip install pandas numpy
```
# Below is a screenshot of the output
Move the pointer to the output to see the hover effect
<p align="center">
  <img width="" height="" src="https://github.com/AntonyGN/Python-hover-effect/blob/main/Screen%20Shot%202023-03-18%20at%208.17.03%20PM.png">
</p>

# Contributing
If you find any issues or bugs in this script, or have suggestions for improvement, feel free to open an issue or pull request in the repository. Contributions are always welcome!

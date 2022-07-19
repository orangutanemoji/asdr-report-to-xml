# asdr2xml

This script automates point creation for desigo. It takes an ASDR file in `.csv` format outputs an `.xml` file with the same name and location. You will need a Python environment with Jupyter Notebook support, such as VS Code.

On the initial run, the required libraries can be installed by setting `FIRST_RUN` to True.

File locations are referenced in relation to `asdr2xml.ipynb`, for example, the location for the current test data is located with `asdr_filename = 'DVO/ASDR.csv`

There are still some edge cases that the script does not support, but it will assign most of the points.

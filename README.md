# asdr2xml

This script automates point creation for Desigo CC. It takes an ASDR file in `.csv` format and outputs an `.xml` file with the same name and location. In order to run the `.ipynb` file, you will need a Python environment with Jupyter Notebook support, such as VS Code.

On the initial run, the required libraries can be installed by setting `FIRST_RUN` to True.

File locations are referenced in relation to `asdr2xml.ipynb`. The location for the repository's test data set in the script with `asdr_filename = 'DVO/ASDR.csv`

There are still some edge cases that the script does not support, but it assigns most of the points.

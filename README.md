# Matrix-Calculator
Bash shell scripts to generate matrices and perform simple matrix calculations on them.

# matrix script
The main script in this file is called **matrix**, and the usage options are:

    matrix dims [MATRIX]
    matrix transpose [MATRIX]
    matrix mean [MATRIX]
    matrix add MATRIX_LEFT MATRIX_RIGHT
    matrix multiply MATRIX_LEFT MATRIX_RIGHT

**NOTE:** The input should be whole number values separated by tabs into a rectangular matrix.

The script can print the dimensions of a matrix, transpose a matrix, calculate the mean vector of a matrix, calculate two matrices, and multiply two matrices.

The following are example of *invalid* matrices:

    * An empty matrix.
    * A matrix where the final entry on a row is followed by a tab chracter.
    * A matrix with empty lines.
    * A matrix with any element that is blank or not an integer.
    
# Helper scripts
A couple of helper scripts are **generate**, written by Ryan Gambord, to generate matrix files in the appropriate format, and **clean**, which cleans the current working directory of any temporary files.

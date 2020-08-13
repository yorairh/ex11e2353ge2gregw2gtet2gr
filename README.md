# First Assignment
Creating a library about Matrix
* Struct Matrix - int height, int width, int** values
* Enum ErrorCode - ERROR_SUCCESS = 0, ERROR_FAILURE = 1
# Matrix functions:
* matrix_create - Creates a new matrix of a given height an width, all values are initially zeroes.
* matrix_copy - Creates a new matrix from an old matrix.
* matrix_destroy - Destroys a matrix.
* matrix_getHeight - Returns the height of a given matrix.
* matrix_getWidth - Returns the width of a given matrix.
* matrix_setValue - Sets a value to the matrix.
* matrix_getValue - Gets a value from the matrix.
* matrix_add - Computes the addition of two matrices.
* matrix_multiplyMatrices - Computes the multiplication of two matrices.
* matrix_multiplyWithScalar - Multiplies a matrix with a scalar and stores the result in the given matrix.

All the functions except the destroy function return an ErrorCode enum

# ErrorCode functions:
* error_isSuccess - Checks if a given error code indicates a success or not.
* error_getErrorMessage - gets a textual error message for a given error code.

# NumPy Tutorial

This notebook explores fundamental concepts and operations in the NumPy library for numerical computing in Python.

## Array Creation and Properties

- Creating arrays from Python lists.
- Checking array type and dimensions (`ndim`).
- Creating arrays with a specified number of dimensions (`ndmin`).
- Creating arrays filled with zeros (`zeros`).
- Creating arrays filled with ones (`ones`).
- Creating empty arrays (`empty`).
- Creating arrays with a range of values (`arange`).
- Creating identity matrices (`eye`).
- Creating evenly spaced values within an interval (`linspace`).
- Creating arrays with random numbers (`random.rand`, `random.randn`, `random.ranf`, `random.randint`).

## Data Types

- Understanding different data types in NumPy arrays (`dtype`).
- Converting data types of arrays.

## Arithmetic Operations

- Performing element-wise arithmetic operations between arrays and scalars.
- Performing element-wise arithmetic operations between two arrays.
- Using NumPy's arithmetic functions (`add`, `subtract`, `multiply`, `divide`, `mod`, `power`, `reciprocal`).
- Performing arithmetic operations on 2D arrays.

## Arithmetic Functions

- Using common arithmetic functions like `max`, `min`, `argmin`, `argmax`, `sqrt`, `sin`, `cos`, `cumsum`.
- Applying arithmetic functions to 2D arrays along specific axes.

## Shape and Reshaping

- Checking the shape of an array (`shape`).
- Reshaping arrays into different dimensions (`reshape`).
- Reshaping to a 1D array (`reshape(-1)`).

## Broadcasting

- Understanding broadcasting rules and errors.

## Indexing and Slicing

- Accessing elements in 1D, 2D, and 3D arrays using indexing.
- Slicing arrays to extract subsets of elements.

## Iteration

- Iterating through array elements using standard Python loops.
- Iterating through arrays using `np.nditer`.
- Iterating through arrays with index using `np.ndenumerate`.

## Copy vs View

- Differentiating between copying and viewing arrays and how changes affect the original and new arrays.

## Join and Split

- Joining arrays using `concatenate`, `stack`, `hstack`, `vstack`, and `dstack`.
- Splitting arrays using `array_split`.

## Search, Sort, and Filter

- Searching for elements in an array using `where`.
- Searching for insertion points in a sorted array using `searchsorted`.
- Sorting arrays using `sort`.
- Filtering arrays based on a boolean mask.

## Other Functions

- Shuffling array elements randomly using `shuffle`.
- Finding unique elements in an array using `unique`.
- Resizing arrays using `resize`.
- Flattening arrays to 1D using `flatten` and `ravel`.

## Insert and Delete

- Inserting elements into an array using `insert`.
- Appending elements to an array using `append`.
- Deleting elements from an array using `delete`.

## Matrix Operations

- Creating NumPy matrices.
- Performing arithmetic operations on matrices (including dot product).
- Using matrix functions like `transpose`, `swapaxes`, `linalg.inv` (inverse), `linalg.matrix_power`, and `linalg.det` (determinant).

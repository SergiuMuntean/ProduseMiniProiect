# ProduseMiniProiect(English: ProductsMiniProjects)

## Description

The **Product Tracker** is a C program designed to read an array of products from an input file, process it based on a task, and output the results to another file. The tasks include counting products based on a condition or sorting them based on their first and second digits.

## Features

1. **Task 1**: Count products based on the second digit (even or odd).
2. **Task 2**: Sort products by the first digit, then by the value.

## Files

- **produse.in**: Input file containing the product data.
- **produse.out**: Output file where the results are written.

## Functions

- **readArray(FILE* input, int* array, int* cerinta, int* size)**: Reads the array and task type from the input file.
- **extractFirstDigit(int number)**: Extracts the first digit of a given number.
- **extractSecondDigit(int number)**: Extracts the second digit of a given number.
- **stockProductsNotAvailable(FILE* output, int* array, int size)**: Counts and outputs the number of products with even or odd second digits.
- **sortProducts(int* array, int size)**: Sorts the products based on the first digit and their values.
- **displayProducts(FILE* output, int* array, int size)**: Displays the sorted products.

## Compilation

To compile and run the program, use:

```bash
gcc -o product_tracker product_tracker.c
./product_tracker
```

## Example Input
2 5
123 456 789 321 654

## Example Output
1 123 321 
2 456 654 
3 789

# License
This project is licensed under the MIT License.


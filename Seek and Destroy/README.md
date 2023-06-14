# Function: destroyer

The destroyer function removes specified values from an array and returns a new filtered array.

## Usage

const result = destroyer(arr, ...valsToRemove);

arr (Array): The original array to be filtered.

...valsToRemove (Any): The values to be removed from the array.

The function returns a new array that excludes the specified values.

Example

const arr = [1, 2, 3, 4, 5];
const result = destroyer(arr, 2, 4);
console.log(result);
// Output: [1, 3, 5]

In the example above, the destroyer function is called with an array [1, 2, 3, 4, 5] and values 2 and 4 as arguments. 
The resulting array is [1, 3, 5] as the values 2 and 4 are removed from the original array.

Note: It is recommended to use the rest parameter syntax (...valsToRemove) for improved readability and compatibility with arrow functions.

## License
This project is licensed under the MIT License. 









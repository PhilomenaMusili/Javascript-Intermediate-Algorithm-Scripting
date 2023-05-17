# TruncateString

The truncateString function is a utility function that truncates a given string if its length exceeds a specified number of characters. It is commonly used to shorten text while preserving readability.

# Usage

truncateString(str, num)

str (string): The input string to be truncateId.

num (number): The maximum number of characters allowed in the truncated string.

Return Value

The function returns a truncated version of the input string.

If the length of str is greater than num, the function will truncate the string by slicing it from the beginning and appending ellipsis ("...") to indicate the truncation.
If the length of str is less than or equal to num, the function will return the original string without any modification

Example
const result = truncateString("A-tisket a-tasket A green and yellow basket", 8);
console.log(result);
// Output: "A-tisket..."

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

# License
This project is licensed under the MIT License.


# JavaScript Empty Array toString() Behavior
This repository demonstrates a subtle bug in JavaScript related to the behavior of `toString()` on empty arrays. The provided code intends to convert various input types to their string representation. However, it unexpectedly returns an empty string for empty arrays. This might lead to unexpected behavior in applications where a more descriptive representation is needed.

## Bug Description
The `foo` function attempts to convert different data types to strings. While it correctly handles null, undefined, numbers, booleans, and objects, it unexpectedly returns an empty string for empty arrays.  A more robust solution would explicitly handle this case and return a more informative string.

## Solution
The solution provided offers a more robust method to convert various data types to strings, explicitly checking for and handling empty arrays with a user-defined string representation.

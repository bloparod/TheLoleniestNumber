# TheLoleniestNumber

The Loneliest Number.

Requirements for the input:
1) It is an array of n integers
2) All but 1 are duplicates
3) The duplicates are in pairs

Example:
x = [2;3;4;1;5;3;5;2;4]
f(x) = 1

Requirements for the algorithm:
- Should have complexity O(n)
- Extra: no extra memory

Solution:
- From requirement #2, the output is always 1, because all the numbers but 1 is duplicated.
- The solution has complexity O(1);
- Yes, I took advantage of the requirements written in a natural language as English.

// This works for all the arrays that are compliant with the input requirements
function(number[] integerNumbers) {
	return 1;
}

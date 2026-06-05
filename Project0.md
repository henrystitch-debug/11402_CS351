# Project 0 — Two Sum

## Goal

In this project I implemented the classic "two sum" problem: given an array of integers and a target value, return indices of the two numbers that add up to the target. The goal of Project 0 is a small, well-tested implementation with two function variants and an associated test suite.

## Requirements

- Provide two implementations of two_sum:
	- A straightforward brute-force implementation (O(n^2)).
	- An efficient hash-map implementation (O(n) average).
- Include unit tests that cover typical cases, edge cases, and error conditions.

## Implementation

Functions
- twoSumLoop
	- Iterate all pairs (i, j) with i < j and return the first matching pair of indices.
- twoSumHashmap
	- Iterate once over nums, store seen values in a dict mapping value -> index.
	- For each value x, check if (target - x) is already in the dict; if so return (index_of_complement, current_index).

## Tests

- Basic Positive Numbers, e.g. [2,7,11,15], target 9 -> (0,1)
- Negative Numbers, e.g. [-3,3,-1,6], target -4 -> (0,2)
- Zero as part of the Solution, e.g. [2,0,11,15], target 11 -> (1,2)
- Duplicate Values, e.g. [2,4,9,4], target 8 -> (1,3)
- No Solution, e.g. [2,7,11,15], target 50 -> NULL
- Large Array ->  Performance Comparison 


## Challenges

- Ambiguity in problem statements: It wasn't specified  what to do if there is multiple solutions and what to do if no solution exists. 
- Project Structure: Creating the codes, files and test cases from scratch, find out how it works together. 
- Temptation of AI: Remember to think of solution first and attempt implementing code first before immediately turning to AI to actually understand the code.
- Working with AI-generated code: Remember that while AI can quickly scaffold solutions, it can introduce subtle bugs. Always review and test AI-suggested code.

## Best Practices

- Treat AI output as a draft: verify logic, style, and make sure the output is understood.
- Write clear, minimal prompts: describe expected input/output, complexity constraints, and error behavior.
- Use tests as the source of truth: create unit tests after AI-generated code to validate behavior.
- Create readable and maintainable code for others to understand.

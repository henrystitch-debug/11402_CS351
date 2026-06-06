# Project B — CSV Mini Database

## Goal

The goal of this project was to build a mini database engine in C++ capable of loading CSV files and executing basic database operations. The project was designed to provide hands-on experience with data processing, file handling, object-oriented programming, and query execution.

## Requirements

The project required the implementation of a lightweight database system with the following functionality:

- Load and parse CSV files.
- Store tabular data in memory.
- Execute basic query operations like SELECT, ORDER BY and aggregate functions.
- Handle invalid input and edge cases appropriately.
- Create and run tests to validate functionality.

## Implementation

The mini database was developed from scratch in C++. 

Main Functions:
- loadCSV(): CSV file loading and parsing
- reset(): Restore original dataset
- executeQuery(): Calls corresponding query function
- selectClumn(): Returns only a specific column
- sortBy(): Sorting records based on specified columns.
- agregate(): Aggregate operations for numerical analysis.
- exportResults(): export results after query execution as a new CSV file

## Tests

Unit and integration tests to verify correctness.

Main Functions:
- Loading the Dataset
- Reseting the Dataset
- Filter Numeric columns
- Filter String Columns
- Sort Rows
- Aggregate Functions
- Chaining Queries
- Edge Cases

## Challenges

- One of the main challenges was learning and working with C++, as I had little to no prior experience with the language before starting this project. Understanding C++ syntax, memory management concepts, and common programming patterns required additional effort compared to working in a more familiar language.

- Building the entire system from scratch without an existing codebase. Designing the data structures, query execution logic, and file parsing mechanisms required careful planning and problem-solving.

- Responsible use of Artificial Intelligence tools, rather than copying generated code directly. It was important to understand the solutions provided and verify that they matched the project requirements. Since I was still learning C++, reviewing and validating AI-generated code was often challenging but also served as a valuable learning experience.

## Best Practices

Throughout the project, several best practices proved especially useful:

- Write the logic yourself before asking AI for help.
- Use AI as a learning tool rather than a source of copy-paste solutions, then ask AI to convert it to C++
- Review AI-generated code line by line to ensure you understand how it works.
- Keep functions small and focused on a single responsibility.

By following these practices, the project became both a software engineering exercise and an opportunity to learn C++ while gaining experience with responsible AI-assisted development.

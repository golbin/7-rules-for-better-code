# 7 simple rules for better code

## 1. Separate into another function when lines of a function are over one page
Based on a 12 "notebook, it's usually up to 25 lines including comments.

## 2. Separate into another function when an indentation is over two levels
When a for statement or an if statement occurs, think about it once again.

## 3. Separate into another function if you need to write comments
The block could be separated by semantics. Try to summarize the comments as a function name.

## 4. Separate into another module(file) or classes when you need to add data of a new type.
A program is basically a combination of data and algorithms process the data.

## 5. Use linting and formatting tool always
Recommended linting and formatting tools contain most of the best practices.

## 6. Start with a refactoring at least one line before adding or modifying functions.
It is also good to warm up brain

## 7. Start with just one test case
Even if it's not available now, it makes easy to add tests next time when adding, modifying, or refactoring your functions.

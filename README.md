# Regular Expressions in Python 🐍✍️💻

## 1. Description 👇

This guide provides practical examples focused on using **Regular Expressions (Regex)** in Python.

It covers string manipulation techniques, pattern matching, and advanced regex usage, based on the exercises from the [Regular Expressions in Python course at DataCamp](https://app.datacamp.com/learn/courses/regular-expressions-in-python).

The project is organized into the following sections:

```sh
.
├── README.md
├── data
│   ├── short_movies.csv
│   ├── short_tweets.csv
│   └── wikipedia.csv
└── notebooks
    ├── Part 1. Strings Operations.ipynb
    └── Part 2. Regular Expressions.ipynb
```

- **data/**: Contains the raw data and the processed data.
- **notebooks/**: Jupyter Notebooks for each part of the course, including hands-on examples of string operations and regex applications.

## 2. Technology stack 💻

### Programming language

- [Python](https://docs.python.org/3/)

### Python Libraries

- [re](https://docs.python.org/3/library/re.html): Regular expressions for working with strings.

To use the library in your code, simply import it, **as you will see in the noteboks:**

```sh
import re
```

## Wrap-Up: String Operations in Python

This section highlights key operations for working with strings in Python, with practical examples for each.

### 1. **Changing Case**

- Convert to lowercase: `my_string.lower()`
- Convert to uppercase: `my_string.upper()`
- Capitalize the first character: `my_string.capitalize()`

### 2. **Splitting Strings**

- Split at a specified separator: `my_string.split(sep=" ", maxsplit=2)`
- Reverse split starting from the right: `my_string.rsplit(sep=" ", maxsplit=2)`
- Handle escape sequences:
  - `\n`: Moves text to a new line.
  - `\r`: Moves the cursor to the start of the line, overwriting existing text.

### 3. **Joining Strings**

Concatenate elements of a list or iterable into a single string using a separator:

```sh
" ".join(["this", "is", "a", "string"])  # Output: "this is a string"
"_".join(["this", "is", "a", "string"])  # Output: "this_is_a_string"
```

### 4. **Stripping & Trimming**

- Remove characters from both ends: `.strip()`
- Remove characters from the right end: `.rstrip()`
- Remove characters from the left end: `.lstrip()`

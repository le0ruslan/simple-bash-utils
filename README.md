# simple-bash-utils

`simple-bash-utils` is a collection of utilities implemented in Bash, designed to replicate the functionality of popular Linux tools. The primary goal of this project is to learn and demonstrate the principles behind command-line utilities.

## Features

The project includes the following utilities:

1. **cat** — an alternative to the `cat` command for viewing file contents.
2. **grep** — an alternative to the `grep` command for searching lines matching a pattern.
3. **other-utils** — additional functions and utilities to enhance basic functionality.

Each utility was developed as a learning project to explore the capabilities of Bash scripting.

## Highlights

- Fully implemented in Bash.
- Works on Linux and macOS.
- Minimal dependencies.
- Simple structure and readable code, making it a great example for learning.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/le0ruslan/simple-bash-utils.git
    ```

2. Navigate to the project directory:
   ```bash
    cd simple-bash-utils/src/cat
    ```
   or
   ```bash
    cd simple-bash-utils/src/grep
    ```

3. To compile utils, execute:
   ```bash
    make
    ```

## Usage
### cat
To view the contents of a file, run:

   ```bash
    ./s21_cat file.txt
   ```
### grep
To search for lines containing a specific pattern:

   ```bash
    ./s21_grep "pattern" file.txt
   ```

## Requirements
* Bash version 4.0 or higher.
* Linux or macOS.

## Testing
To run tests, execute:

   ```bash
    simple-bash-utils/src/cat
   ```
or
   ```bash
    simple-bash-utils/src/grep
   ```

and
   ```bash
    make test 
   ```
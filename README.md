# Project Name: LL(1) and LR(0) Parser

## Description
This project implements LL(1) and LR(0) parsers to analyze grammars and strings provided by the user. It allows processing strings, verifying whether a grammar is LL(1), and performing both bottom-up and top-down syntactic analysis. The implementation is designed to be extendable and easy to use in educational or research applications in the field of programming language theory.

## Features
- String analysis using LL(1) and LR(0) parsers.
- LL(1) grammar verification.
- Generation of First and Follow sets for grammars.
- Bottom-up and top-down syntactic analysis.

## Installation
The project does not require the installation of external dependencies beyond standard Python. To run it, clone the repository to your local machine:

Follow the console instructions to select between LL(1) and LR(0) analysis, enter strings for analysis, and more. There are example grammars in the tests folder, from which you can take the format to use your own.

### Example of use:
1. Run the script: `python main.py`
2. Select the type of grammar by entering `1` for LL(1) or `2` for LR(0).
3. Choose the desired operation (process string, show First and Follow, verify if the grammar is LL(1), etc.).
4. If you choose to process a string, enter it when prompted.

## Contributing
This project is open source, and contributions are welcome. If you want to contribute improvements, fix a problem, or add functionalities, please fork the repository and send a pull request with your changes.

# Student Data Management System 

## Overview:
This project demonstrates the practical use of core Python data structures and data processing techniques.  
The system stores, filters, and processes student records efficiently using:

- Lists
- Tuples
- Dictionaries
- Sets
- List Comprehensions
- Dictionary Comprehensions
- Generator Expressions

The project is modular, readable, and designed to showcase structured data handling in Python.

---

## Learning Objectives

This lab demonstrates:

- Proper use of Python data structures
- Efficient filtering using list comprehensions
- Dictionary creation using dictionary comprehension
- Tracking unique values using sets
- Memory-efficient processing using generator expressions
- Clean modular code organization
- Git workflow best practices

---

##  Project Structure


course-7-module-1-python-data-structures-lab/
│
├── lib/
│ ├── student_data.py
│ ├── filters.py
│ ├── data_processing.py
│ ├── set_operations.py
│ ├── data_generator.py
│ └── init.py
│
├── testing/
│ ├── test_filters.py
│ ├── test_data_processing.py
│ ├── test_set_operations.py
│ ├── test_data_generator.py
│ └── init.py
│
├── Pipfile
├── Pipfile.lock
└── README.md


---
## Setup Instructions

### Fork and Clone the Repository

 1. Go to the provided GitHub repository link.
 2. Fork the repository to your GitHub account.
 3. Clone the forked repository to your local machine using:
   ```sh
   git clone <repo-url>
   cd course-7-module-1-python-data-structures-lab
   ```

### Install Dependencies

Ensure **Python** is installed:
```sh
python --version
```

Run the following command to install dependencies:
```sh
pipenv install
```

Run the following to enter the virtual environment:
```sh
pipenv shell
```

To run the test suite, use:
```sh
pytest -x
```

## Conclusion

This project demonstrates structured and efficient use of Python data structures.
It highlights:

Clean modular design

Proper use of comprehensions

Efficient memory usage with generators

Maintainable and readable code

The system is scalable and suitable for handling larger datasets with minimal modification.

# Unittests and Integration Tests

This repository contains a collection of Python scripts and corresponding unit tests and integration tests using the unittest framework. The scripts are designed to perform various tasks related to testing functionalities of utility functions, HTTP requests, and class methods.

## Table of Contents
1. [Requirements](#requirements)
2. [File Structure](#file-structure)
3. [Tasks](#tasks)
4. [How to Use](#how-to-use)
5. [Author](#author)

## Requirements
All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/env python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the pycodestyle style (version 2.5)
All your files must be executable
All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
All your functions and coroutines must be type-annotated.

## File Structure

1. utils.py: Contains utility functions for testing.
2. client.py: Contains classes for HTTP client functionalities.
3. fixtures.py: Contains fixtures used for integration tests.
4. test_utils.py: Unit tests for utils.py.
5. test_client.py: Unit and integration tests for client.py.


## Tasks
1. Parameterize a unit test: Write unit tests for access_nested_map function.
2. Parameterize a unit test: Implement unit tests for error handling in access_nested_map function.
3. Mock HTTP calls: Write unit tests for get_json function using unittest.mock.patch.
4. Parameterize and patch: Implement unit tests for memoization decorator.
5. Mocking a property: Unit test for _public_repos_url method in GithubOrgClient class.
6. More patching: Unit test for public_repos method in GithubOrgClient class.
7. Parameterize: Unit test for has_license method in GithubOrgClient class.
8. Integration test: fixtures: Integration tests for public_repos method in GithubOrgClient class using fixtures.

## How to Use

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the unit tests using the command python3 -m unittest discover -v.
Enjoy testing your Python scripts with confidence!

## Author
This repository is maintained by Ginika Elizabeth. Feel free to reach out with any questions or suggestions!


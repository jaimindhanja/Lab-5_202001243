# Lab5_202001243

## IT314 - Software Engineering
## Lab 5 - Static Analysis 

### Name: Dhanja Jaimin Narendrabhai
### Student ID: 202001243

============================================================================================

> Doing the static analysis of a random git repository using the ‘mypy’ tool. 

* The reference git repository link: https://github.com/qxf2/wtfiswronghere.git

* The command to install mypy on the command line: 
python -m pip install mypy 

* The command to find errors in the repository: 
python -m mypy <file_path>

* The following screenshot shows how the static analysis is performed using mypy tool: 

### Steps

 1. First cloning a random git repository.
## ![image](https://user-images.githubusercontent.com/124347700/227492986-fa0431a0-847b-409b-a60a-3b12a72e68b9.png)
2. Then running the command for finding errors.
## ![image](https://user-images.githubusercontent.com/124347700/227493241-fc751474-8463-4781-b32b-b6217d5c9a76.png)
## ![image](https://user-images.githubusercontent.com/124347700/227493307-05547dac-ffd2-48da-bf7a-179fd128c03f.png)
## ![image](https://user-images.githubusercontent.com/124347700/227493504-46c284f5-8edf-45bc-96d0-a8a04fdf5912.png)
## ![image](https://user-images.githubusercontent.com/124347700/227493645-6e8f53df-a306-4501-8553-426b8fe670f3.png)
## ![image](https://user-images.githubusercontent.com/124347700/227493924-ae00bc06-1bc6-443c-8a09-b528c87e721d.png)
## ![image](https://user-images.githubusercontent.com/124347700/227494020-99f31e40-50e1-4d79-a5d8-f2c553b3e699.png)
## ![image](https://user-images.githubusercontent.com/124347700/227494300-917b27b7-304b-48bb-9b10-a250982a05a5.png)
## ![image](https://user-images.githubusercontent.com/124347700/227494356-f4b60001-823c-414d-a3bf-4f50557b8a44.png)

* The screenshots up top demonstrate that a couple of the repository's files contain a few problems, which are displayed beneath the command.
* A small number of files also lack the errors that are also presented.


___________________________________________________________________________________________

### Analysis of Tool (mypy) : 
* The syntax problems that are present in the majority of files are one type of error that this programme can identify.
* Also, it locates a few files with call-arguments issues.
* It shows a comment that nearly describes the issue and is also clear, which aids in code debugging.
* This tool checks that the types of variables, function parameters, and return values are consistent with their type annotations. This helps to catch type-related errors before they occur at runtime.
* The majority of IDEs, editors, and continuous integration pipelines can be used with this tool to integrate it into development environments and build systems.
* Mypy allows developers to enact their own coding standards and plugins because it offers custom type checking rules.

___________________________________________________________________________________________

### Understanding of Errors : 
* Mypy is a static type checker for Python that aids in identifying common mistakes and enhancing code quality. Mypy examines the code and looks for type mistakes when you run it on your Python programme.

* Type mistakes happen when a value of one type is used in a situation where it is incompatible with another type. Mypy will raise a type error, for instance, if you attempt to combine a string and an integer.

* When Mypy finds a type problem, it will notify the user with an error message that includes the code's position. An explanation of the issue and advice on how to remedy it will both be included in the error message.


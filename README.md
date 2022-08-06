# C_Project_Concept
Important concepts regarding C
### stdarg.h
* `stdarg.h` is a header in the C standard library of the C programming language that allows functions to accept an indefinite number of arguments
* Its contents are typically used in variadic functions
* Variadic functions are functions which may take a variable number of arguments
#### stdarg.h types
* **va_list** --> Type for iterating arguments
* **va_start** --> Start iterating arguments with a va_list
* **va_arg** --> Retrieve an argument
* **va_end** --> Free a va_list
* **va_copy** --> Copyt contents of one va_list to another

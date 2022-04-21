# - printf
## Description
This team project is part of the first year curriculum of ALX School.
```c _printf ``` replicates the C standard library printf() function.
### What you should learn from this project:
- How to use git in a team setting
- Applying variadic functions to a big project 
- The complexities of printf
- Managing a lot of files and finding a good workflow
## Prototype
``` c int _printf(const char *format, ...); ```
## Usage
- Prints a string to the standard output, according to a given format
- All files were created and compiled on ```Ubuntu 20.04.4 LTS and windows using GCC 4.8.4``` with the 
- command ``` bash gcc -Wall -Werror -Wextra -pedantic *.c```
- Returns the number of characters in the output string on success, -1 otherwise
- Call it this way: ```c _printf("format string", arguments...)```
- where format string can contain conversion specifiers and flags, along with regular characters
## Scope of this Function
This is what it can do 
- It can write ```strings, characters, numbers, addresses```
- It can do Datatype conversion controlled by the converter file
This function developed in the project doesn't consider these cases 
- field width
- precision or  (type precision from a mathematical standpoint)
- the length modifiers
This class project it doesn't consider edge cases and industrial standards.
The manual page are not exhaustive.
## Authors and Collaborators  
- [Michael Goboola](https://github.com/michaelgobz)
- [Fred Osege](https://github.com/suffskills)
- Alx Software Engineering Program ```Cohort 5 (2022)```

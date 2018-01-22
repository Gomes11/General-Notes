### Shell Script

## Notes from experience
1) Shell script files are recognized by the operating system as such by the the mark '#! /bin/sh'. This specifies the usage of the most basic shell interpreter in the operating system.
2) Shell is a scripting language, thus there are no compilers available by default for it. The act of 'debugging' shell script files consists in following the flux of data and/or print (a.k.a. echo/puts) commands that are executed at runtime and produce their output as re execute the sript itself.
3) Shell works as any other scripting language such as python, tcl, ruby, etc, the major difference is that most of linux tools are written either in C or in shell, which makes it much easier to communicate with the operating system.

## Basic commands
- ***Printing*** <br/>
The most standard ways of printing content in shell:
   * echo
   * printf
  
- ***Setting Variables*** <br/>
  There is no specific predicate in shell to set a variable, thus something like `'var="foo"'` or `'var=bar'` would work.

- ***Looping*** <br/>
  The most simple way of looping through values in shell is using either a `for` or a `while` loop. Those work alike in any other language, as follows:
  * `for ((var=0; var<5; var++)); do command done`
  
  * `for variable in command; do command done` 
  

- ***Input/Output*** <br/>

- ***Piping Commands*** <br/>

---
layout: default
title: Variables
parent: Javascript Best Practices
---
# [Javascript best practices](./Contents.md)
## Variables

* Avoid global variables
   * variables created outside of a function are global variables
   * variables created with no keyword are global variables 
* Use const or let to declare variables
> Include example

* Variables can be accessed in local scope or global scope. 
> Include example

* Local and global variable with the same name => javascript will prioritize the local variable.
> Include example

* Local variables are deleted once the local execution context is complete.
> Include example

* Minifiers can only rename local variables when it is safe to do so.

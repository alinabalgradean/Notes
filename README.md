# Python-vs-all
In this short doc, I'll explore Python vs. other programming languages in terms of various features available/not available.

## Python vs. C++

### Python 
#### Pros
* Very easy to learn (the code looks like pseudo-code)
* No integer overflow (arbitrary precision)
* Significantly less time to develop compared to C++
* Nearly 20,000 libraries available
* Garbage collection
* No need to create data structures from scratch
* No need to worry about the data types (interpreter based language - dynamic typing)
* Interpreted (statements are executed one by one, debugging is easier than in C++)
#### Cons
* Dynamic typing - very error prone (e.g. especially when it comes to iterations or different data structures that share common access methods)
* Relatively slow (when compared to C++, Java and Go)
* Needs an interpreter -> no low-level work
* Hard to decide what library/framework to use as there are frequently many choices
* Not suitable for large scale development
* Python has thread support, but because of the Global Interpreter Lock (GIL) it's not normally worth the effort. If parallelism is required in Python, you are better off going with the interprocess modules

### C++
#### Pros
* Allows low level hardware access and direct access to memory
* If properly written, it's usually the fastest
#### Cons
* Verbose (takes quite a lot of time to develop)
* Higher levels of complexity

### Features that you'd like Python to have from C++

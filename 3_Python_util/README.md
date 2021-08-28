## Python module and package
### Module
> There are actually three different ways to define a module in Python:
>> * A module can be written in Python itself.
>> 
>> * A module can be written in C and loaded dynamically at run-time, like the re (regular expression) module.
>> 
>> * A built-in module is intrinsically contained in the interpreter, like the itertools module.
>> 
>> Here, the focus will mostly be on modules that are written in Python

### Import (module search path)
    import sys
> When the interpreter executes the above import statement, it searches for sys.py in a list of directories assembled from the following sources:
>> * The directory from which the input script was run or the current directory if the interpreter is being run interactively
>> * The list of directories contained in the PYTHONPATH environment variable, if it is set. (The format for PYTHONPATH is OS-dependent but should mimic the PATH environment variable.)
>> * An installation-dependent list of directories configured at the time Python is installed

    import sys    
    sys.path
    
    ['', 'C:\\Users\\chs\\Documents\\Python\\doc', 'C:\\Python36\\Lib\\idlelib','C:\\Python36\\python36.zip',  'C:\\Python36\\DLLs', 'C:\\Python36\\lib', 'C:\\Python36', 'C:\\Python36\\lib\\site-packages']
    
### Package
#### See pkg_example_1 & pkg_example_2



##### https://realpython.com/python-modules-packages/ for more details...


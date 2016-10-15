
# Chapter 22: Changing Environment Variables (export)

## Do More

### Take and list out all the environment variables you've found and then go look up what they are online (please do 5-10 or so).

I used ```env``` to pull up the list of environment variables. I won't list them all here, but here are a few:
```
HOME=/Users/tommy.haggerty
RUBY_VERSION=ruby-2.3.1
rvm_path=/Users/tommy.haggerty/.rvm
PWD=/Users/tommy.haggerty/workspace/davinci_coders_t3_2016/homework/learn_command_line_exercises
TERM_PROGRAM=iTerm.app
```
HOME - indicates where a user's home directory is located in the file system
RUBY_VERSION - indicates what your current ruby version is
rvm_path - indicates where the .rvm file is located
PWD - indicates your current working directory
TERM_PROGRAM - indicates your default terminal program

### Read the man page for env again. What else can it do?

```
-i      Execute the utility with only those environment variables specified by name=value options.  The environment inherited by env is
        ignored completely.

-P altpath
        Search the set of directories as specified by altpath to locate the specified utility program, instead of using the value of the
        PATH environment variable.

-S string
        Split apart the given string into multiple strings, and process each of the resulting strings as separate arguments to the env
        utility.  The -S option recognizes some special character escape sequences and also supports environment-variable substitution,
        as described below.

-u name
        If the environment variable name is in the environment, then remove it before processing the remaining options.  This is similar
        to the unset command in sh(1).  The value for name must not include the `=' character.
        
-v      Print verbose information for each step of processing done by the env utility.  Additional information will be printed if -v is
        specified multiple times.   
```


# Chapter 8: Moving around (pushd, popd)

## Do More

### Use these commands to move around directories all over your computer.

    I used pushd Users/tommy.haggerty/workspace to move to the main directory, then
    popd to go back to /Users/tommy.haggerty/workspace/davinci_coders_t3_2016/homework/learn_command_line_exercises/tmp
    I used pwd to verify where I was after each command.
    
### Remove the i/like/icecream directories and make your own, then move around in them.

    Making some assumptions I used rmdir -p i/like/icecream to remove the path all at once,
    I then used mkdir -p I/also/like/steak , to create a new path. I used pushd to jump to part
    of the path then popd to jump back. Finally I used rmdir -p I/also/like/steak to remove 
    that path again.
    
### Explain to yourself the output that pushd and popd print out to you. Notice how it works like a stack?

    The output that pushd and popd displays after it is run is a stack of the paths that are stored.
    When you pushd the list gets longer as you are adding to the stack, 
    when you popd it gets shorter as it pulls stuff off the stack.

### You already know this, but remember that mkdir -p will make an entire path even if all the directories don't exist. That's what I did very first for this exercise.

    This is true, and I also discovered that rmdir -p will remove the entire path, assuming it is an empty path.
    

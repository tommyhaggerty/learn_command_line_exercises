
# Chapter 17: Finding files (find)

## Do More

### Unix: Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print". Next time you drill make sure you can say that phrase so you remember how find is formatted.

Done

### You can put any directory where the . (dot) is. Try another directory to start your search there.

```
find lrthw_exercises/ ".txt" -print | less
```

### Look for all the video files on your computer starting at the home drive and use the > to save the list to a file. Remember how you can do SOMECOMMAND > SOMEFILE.txt and it will write the output of SOMECOMMAND to the file SOMEFILE.txt?

```
find . -name "*.mp4" -print > ~/workspace/davinci_coders_t3_2016/homework/learn_command_line_exercises/tmp/videofile.txt
```

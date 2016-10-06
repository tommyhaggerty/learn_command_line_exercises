
# Chapter 9: Making Empty Files (Touch)

## Do More

### Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

```
Tommys-MacBook-Pro:tmp tommy.haggerty$ cd ..
Tommys-MacBook-Pro:learn_command_line_exercises tommy.haggerty$ mkdir tmp2
Tommys-MacBook-Pro:learn_command_line_exercises tommy.haggerty$ cd tmp2
Tommys-MacBook-Pro:tmp2 tommy.haggerty$ touch newblankfile.txt
Tommys-MacBook-Pro:tmp2 tommy.haggerty$ cd ..
Tommys-MacBook-Pro:learn_command_line_exercises tommy.haggerty$ ls

README.md		do_more_chapter_1	do_more_chapter_15	do_more_chapter_20	do_more_chapter_5	tmp
checkpoint_1		do_more_chapter_10	do_more_chapter_16	do_more_chapter_21	do_more_chapter_6	tmp2
checkpoint_2		do_more_chapter_11	do_more_chapter_17	do_more_chapter_22	do_more_chapter_7
checkpoint_3		do_more_chapter_12	do_more_chapter_18	do_more_chapter_23	do_more_chapter_8
checkpoint_4		do_more_chapter_13	do_more_chapter_19	do_more_chapter_3	do_more_chapter_9
checkpoint_5		do_more_chapter_14	do_more_chapter_2	do_more_chapter_4	foo_bar

Tommys-MacBook-Pro:learn_command_line_exercises tommy.haggerty$ rmdir tmp2
rmdir: tmp2: Directory not empty
```
> The reason there is an error when you try to ```rmdir``` the directory is because
it has a file in it. You can't ```rmdir``` a non-empty directory.

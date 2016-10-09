
If you're not already, please go into the checkpoint_4 directory.

```cd checkpoint_4```

Remove everything in the foo directory using one command

```rm -rf foo```

The following questions are about the file color_preferences.txt.

How many lines are there?

```
cat color_preferences.txt | wc -l
1000
```

How many teenagers are there?

```
grep -c '1[3-9]' color_preferences.txt
320
```
    
Copy the lines from color_preferences.txt to a file called teens.txt, but only include the lines where their age is 13-19.
    
```grep '1[3-9]' color_preferences.txt > teens.txt``` 

How many teenagers like the color purple?

```
grep -c 'purple' teens.txt
14
```    

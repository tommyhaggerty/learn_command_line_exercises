
# Chapter 10: Copy a file (cp)

## Do More
> ***NOTE***: The answers for this chapter should not include the use of cd (change directory).

### Use the cp -r command to copy more directories with files in them.
    
```
Tommys-MacBook-Pro:tmp tommy.haggerty$ ls
awesome.txt		iamcool.txt		neat.txt		newplace		something		thefourthfile.txt
Tommys-MacBook-Pro:tmp tommy.haggerty$ cp -r iamcool.txt tmp2
Tommys-MacBook-Pro:tmp tommy.haggerty$ cp -r awesome.txt tmp2
Tommys-MacBook-Pro:tmp tommy.haggerty$ cp -r thefourthfile.txt foo_bar
```
       
### Copy a file to your home directory or desktop.

```
Tommys-MacBook-Pro:tmp tommy.haggerty$ cp -r iamcool.txt /Users/tommy.haggerty/Desktop
```
    
### Find these files in your graphical user interface and open them in a text editor.

  I have done this. I opened the iamcool.txt file on the desktop
    
### Notice how sometimes I put a / (slash) at the end of a directory? That makes sure the file is really a directory, so if the directory doesn't exist I'll get an error.

I did not recieve any errors when I tried to do the cp without the slash. 
```
Tommys-MacBook-Pro:tmp tommy.haggerty$ mkdir else
Tommys-MacBook-Pro:tmp tommy.haggerty$ cp -r awesome.txt else
Tommys-MacBook-Pro:tmp tommy.haggerty$ ls
awesome.txt		foo_bar			neat.txt		something		tmp2
else			iamcool.txt		newplace		thefourthfile.txt
Tommys-MacBook-Pro:tmp tommy.haggerty$ cd else
Tommys-MacBook-Pro:else tommy.haggerty$ ls
awesome.txt
```
    

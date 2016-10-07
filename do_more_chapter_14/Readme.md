
# Chapter 16: Wildcard Matching

## Do More

### Clean up everything in temp from all the exercises so far

```Tommys-MacBook-Pro:tmp tommy.haggerty$ ls
   else		ex12.txt	ex13.txt	foo_bar		tmp2
   Tommys-MacBook-Pro:tmp tommy.haggerty$ rm else
   rm: else: is a directory
   Tommys-MacBook-Pro:tmp tommy.haggerty$ rmdir else
   rmdir: else: Directory not empty
   Tommys-MacBook-Pro:tmp tommy.haggerty$ rmdir -rf else
   rmdir: illegal option -- r
   usage: rmdir [-p] directory ...
   Tommys-MacBook-Pro:tmp tommy.haggerty$ ls else
   awesome.txt
   Tommys-MacBook-Pro:tmp tommy.haggerty$ rm else/awesome.txt
   Tommys-MacBook-Pro:tmp tommy.haggerty$ rm ex12.txt ex13.txt tmp2 foo_bar
   Tommys-MacBook-Pro:tmp tommy.haggerty$ ls
   else
   Tommys-MacBook-Pro:tmp tommy.haggerty$ rmdir else
   Tommys-MacBook-Pro:tmp tommy.haggerty$ ls
```    
### Write in your notebook to be careful when running recursive remove on files

   Okay

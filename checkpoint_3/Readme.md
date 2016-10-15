
If you're not already, please go into the checkpoint_3 directory.

```cd checkpoint_3```

Can you rename foo/bar/file1.txt to foo/blah.txt?

```mv foo/bar/file1.txt foo/blah.txt```
    
Let's make a copy of foo/blah.txt and put it in the foo/bar/baz directory.

```cp foo/blah.txt foo/bar/baz/```

What happens if you touch an existing file. (Hint:  The answer is not nothing...)

Using ```touch <filename> ``` on an exisiting file changes the time on the file

Can you copy the foo/blah.txt file to slash temp?

Yes. ```cp foo/blah.txt /tmp/```

Can you copy .bash_profile in your home directory to the current directory? (Do not use cd here...)

Yes ```cp ~/.bash_profile ./```

What's in foo/blah.txt?

"This is line xx" where xx counts up from 1 to 5000.
    ```less foo/blah.txt```
    
Can you show me what's in foo/blah.txt one page at a time?

```more foo/blah.txt``` use spacebar to page through or down arrow to line through
one at a time.


If you're not already, please go into the checkpoint_5 directory.

```cd checkpoint_5```

Show me the lines in foo.txt that have "ERROR" in them.

```grep -e "ERROR" foo.txt```

As there are 345 lines found with ```grep -c "ERROR" foo.txt``` I will not be listing
them here unless needed.
   
Show me the lines in foo.txt that have "Synergistic" in them.

```grep -e "Synergistic" foo.txt```

As there are 345 lines found with ```grep -c "ERROR" foo.txt``` I will not be listing
them here unless needed.

What does the -i option to grep accomplish?

-i ignores case when searching with grep

What option to ls tells it to output file size in human readable form?

```ls -h```

What does the -r and -f options to rm do exactly?

-f          Attempt to remove the files without prompting for confirmation, regardless of the file's permissions.  If the file does not
                 exist, do not display a diagnostic message or modify the exit status to reflect an error.  The -f option overrides any previ-
                 ous -i options.
                 
-r          Attempt to remove the file hierarchy rooted in each file argument.  The -R option implies the -d option.  If the -i option is
                 specified, the user is prompted for confirmation before each directory's contents are processed (as well as before the
                 attempt is made to remove the directory).  If the user does not respond affirmatively, the file hierarchy rooted in that
                 directory is skipped.
                 
What does the ifconfig command do?

ifconfig - The ifconfig utility is used to assign an address to a network interface and/or configure network interface parameters.

What is your shell set to?

```
echo $SHELL
/bin/bash
```

What directory are you in (don't use pwd this time)?

```
echo $PWD
/Users/tommy.haggerty/workspace/davinci_coders_t3_2016/homework/learn_command_line_exercises/checkpoint_5
```

What is your home directory set to?

```
echo $HOME
/Users/tommy.haggerty
```

Can you set your environment to have DEBUG set to true?

```
export DEBUG="true"
echo $DEBUG
true
```

Explain how you would change your PATH on your computer

1. Open iterm2
2. Enter ```touch ~/.bash_profile; open ~/.bash_profile```
3. Add the following line to the end of the file adding whatever 
   additional directory you want in your path:
  ```export PATH="$HOME/.rbenv/bin:$PATH"```
4. Save the .bash_profile file and Quit (Command + Q) Text Edit.
5. Force the .bash_profile to execute. This loads the values immediately without having to reboot. 
   In your iterm2, run the following command.
   ```source ~/.bash_profile```
  
Can you remove the debug environment variable?

```unset TESTING```
    
Why is it dangerous to run "rm -rf /". DO NOT RUN THIS COMMAND. Simply explain why it's a very bad idea.

Running this command will delete the files on your computer.

Can you put "This class is fun" into bar.txt?

```
echo 'This class is fun' >> bar.txt
```

Can you put "Oh so much fun" into foo.txt?

```
echo 'Oh so much fun' >> foo.txt
```

Run find in the class directory, pipe the output to pbcopy and create a gist with the content.  Paste the Gist URL below.

    Please use markdown formatting listing the command(s) you ran to accomplish this

    Gist URL:  https://gist.github.com/tommyhaggerty/6319c946cd4133a0d9a35cfde432ac52

Please logout.

```exit```


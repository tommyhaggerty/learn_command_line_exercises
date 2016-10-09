
# Chapter 21: What's in your Environment (env, echo)

## Do More

### I want you to go online and research how you change your PATH for your computer. Try to do it entirely from the CLI.

Step 1: Open up a Terminal window (this is in your Applications/Utilites folder by default)

Step 2: Enter the follow commands:

```touch ~/.bash_profile; open ~/.bash_profile```

This will open the .bash_profile file in Text Edit (the default text editor included on your system). The file allows you to customize the environment your user runs in.

Step 3: Add the following line to the end of the file adding whatever additional directory you want in your path:

```export PATH="$HOME/.rbenv/bin:$PATH"```

That example would add ```~/.rbenv``` to the PATH. The $PATH part is important as it appends the existing PATH to preserve it in the new value.

Step 4: Save the ```.bash_profile``` file and Quit ```(Command + Q)``` Text Edit.

Step 5: Force the ```.bash_profile``` to execute. This loads the values immediately without having to reboot. In your Terminal window, run the following command.

```source ~/.bash_profile```

That’s it! Now you know how to edit the PATH on your Mac OS X computer system. You can confirm the new path by opening a new Terminal windows and running:

```echo $PATH```

You should now see the values you want in your PATH.

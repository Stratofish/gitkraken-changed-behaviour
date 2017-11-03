Add a new file in sub/cache/

GitKraken before 3.2.x would ignore this file. GitKraken 3.2.0 and 3.2.1 show the file as unstaged.

The .gitignore is odd (I assume the two lines cancel each other out so the new behaviour is correct) but doesn't explain the undocumented change in behaviour.

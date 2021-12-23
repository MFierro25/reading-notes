## Python Regular Expression
> Regex: <br>
> a sequence of characters used to check whether a pattern exists in a given text (string) or not

uses:
- validate the format of email addresses
- parsing text data files to find, replace, or delete certain string
- manipulate textual data
- etc..

step 1:
```
import re
```
example: uses regex to find a match
```
pattern = r"Cookie"
sequence = "Cookie"
if re.match(pattern, sequence):
    print("Match!")
else: print("Not a match!")
```

r = raw string literal <br>
^ - matches the start of string  <br>
$ - matches the end  <br>
[abc] - Matches a or b or c.  <br>
[a-zA-Z0-9] - Matches any letter from (a to z) or (A to Z) or (0 to 9).  <br>

<b> at the end of the day regex is a string of text that allows you to create patterns that help match, locate, and manage text </b>

## shutil 
> shutil in Python is a module that has several functions. it deals with operations on files and their collections. It provides the ability to copy and removal of files

example:
```
import shutil
shutil.submodule_name(arguments)
```


## sources 
[1](https://www.datacamp.com/community/tutorials/python-regular-expression-tutorial)
[2](https://pymotw.com/3/shutil/)

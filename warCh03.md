Level 03

It would be easy if level 2 and level 3 had the same way to solve them. Challenge makers had successfuly trapped me in the hidden folder.
The solution was in the bash history.
> ls -a

Since it was a hidden file it was need to use `./` notation as a relative path to the file.
> cat ./.bash_history

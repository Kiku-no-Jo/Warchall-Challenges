# Level 10

This time we need to be very tricky since "solution.txt" is only readable by the administrator.
Let's see the folder's content:
> ls -l

We see `charp` in yellow. It is script which is written in C and it counts `characters number` in a file
> ./charp solution.txt

During my research, I saw that we can have a security breach by exploiting Linux cache. In other words, using the storage of temporary file `/tmp`:
> ./charp "solution.txt | cp solution.txt tmp/newFile.txt"
Congratulations! For solving Warchall's level 10!

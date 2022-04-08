# Linux-Commands-Cheat-Sheet

A compilation of some commonly used Linux commands for beginners (and those of us who often just forget :))

Files & Folders
Some common commands for navigating, moving, deleting & more!

Navigate to a folder
``` 
cd /path/to/folder
```
Create a folder
``` 
mkdir folder
```
Create a folder, then navigate to it (One command)Linux-Commands-Cheat-Sheet
```
mkdir folder && cd folder
```
Move a file or folder to another folder
```
mv /path/to/file.txt /path/to/dest/
mv /path/to/folder1 /path/to/dest/
```
Move multiple folders
``` 
mv folder1 folder2 /path/to/dest/
```
Display files (with details) in a folder
```
ls -l
```
Zip up a file or folder
```
tar -cvzf filename.tar.gz folder/
```
Unzip a file or folder
```
tar -xvzf filename.tar.gz
```
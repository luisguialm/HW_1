# HW_1
## Homework 1 for GEOG693  

## Basic Shell Exercise   

_Problem:_ You are getting ready to input all your field data and metadata from your 25 study sites.  You want to be sure that all your directories and files are organized in exactly the same way but pointing and clicking is time consuming and error prone.  You can solve this by writing a script to make the directories and files for you automagically.

_Objective:_ Create a series of Unix commands that successfully:  
1) Creates the hierarchy of directories and files represented by the diagram on the next page.
2) Then deletes them. You decided to quit your RA and be a river guide.  

Adhere to the following principles:
1)	Make the paths __absolute__ so that I can reproduce the structure on my machine simply by running your code.  
2)	Code should be saved as two blocks of bash commands in an `.md` file  
  * the first block should make the directories  
  * the second block should delete the directories  

3)	Code should include comments that explain each line in your script. These can be written as text around the block in the `.md` or preceded by a `#`.

5)	The fewer lines of code, the better the answer. Edit your answer until only what is required is present. 9 lines of code or less is possible.

#### Example:

##### Jane's Commands

```
pwd #get the current working directory
ls #list the files/folders in the current working directory
mkdir data #makes a new directory called data
rmdir data #deletes directory called data
```

Hints: Here are some commands and flags you might want to use:

`pwd`  
`mkdir -p`  
`touch`  
`cp -r`  
`rm -r -I` #remember to use carefully!





 



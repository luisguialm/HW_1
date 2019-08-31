#Homework 1. Creating directories for a project

## Part I: Creation of folder and files. 
Code to create the directories and files
The first step to to make the directories for the site a. Second step is to create the needed files inside folder site a. Following, we copy site a and create two new folder. The last step is to remove the content of the folders inside site c. 
```{bash}
mkdir -p sites/site_a/{data,metadata,gis} 
touch sites/site_a/data/{plot1.txt,plot2.txt,plot3.txt} sites/site_a/metadata/{plot1.txt,plot2.txt,plot3.txt}
cp -r sites/site_a sites/site_b
cp -r sites/site_a sites/site_c
rm -r sites/site_c/data/* sites/site_c/metadata/*
```

## Part II: Deleting the work. 
An epiphany made you change your mind about completing your PhD and you decide to delete all your work. The folloinw code makes the work:
```{bash}
rm -r -i sites
```
If you are risk adverse, it is a good idea to keep the code to remake your work. Another option is to move the files to a place where you can use them in the future if you change your mind. The following code is an option:
```{bash}
mkdir ~/.trash
mv sites/ ~/.trash
```
_LAG 2019-08-30_

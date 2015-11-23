---
layout: lesson
root: .
title: 
minutes: 20
author: Sheldon McKay
---

# Writing Files at the Command line

Adapted from the lesson by Tracy Teal.
Original contributors:
Paul Wilson, Milad Fatenejad, Sasha Wood and Radhika Khetani for Software Carpentry (http://software-carpentry.org/)

## Learning Objectives
- How to write files while at the command line
- How to open, write in, save and exit from nano

We've been able to do a lot of work with files that already exist, but what
if we want to write or edit our own files. Obviously, we're not going to type in
a FASTA file, but you'll see as we go through other tutorials, there are
a lot of reasons we'll want to write a file, or edit an existing file.

To write in files, we're going to use the program `nano`. We're going to edit the
file we just created *fastqc_summaries.txt*

    $ nano fastqc_summaries.txt

We can edit that file. At the top of the file type

    "This is a summary of a FastQC analysis"

Now we want to save the file and exit. At the bottom of nano, you see the "^X Exit". That
means that we use Ctrl-X to exit. Type `Ctrl-X`. It will ask if you want to save it. Type `y` for yes.
Then it asks if you want that file name. Hit 'Enter'.

Now you've written a file. You can take a look at it with less or cat, or open it up again and edit it.

***
**Exercise**

- Create a new file and in that file type a summary of how to save files in 
nano (it's meta!) and save the file. 

*Tip: If a file with that name doesn't exist already, nano will create it for you when you 
type 'nano filename'. 

***



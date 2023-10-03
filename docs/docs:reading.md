#Project workflows

Bryan 2017

What problems can setwd() cause in your scripts and how do RStudio projects address them?
  Other people will not be able to recreate your file paths. Projects addresses this issue by being self-contained - someone else can open a project and should have everything they need to get the scripts to run.

When you call rm(list=ls()), what is removed from your environment? What’s left over that restarting your R session would remove? What’s the keyboard shortcut for restarting your R session?
  It removes the objects you created from the R workspace. It leaves packages you've loaded and default settings you've changed. Command+Shift+F10 will restart R.

#Version Control

You either read Bryan (2018) or Braga et al. (2023). Answer the questions for the paper you read.

Bryan (2018)

The basic git commands are commit, push, and pull. Which commands change happen locally (i.e., on your computer)? Which happen remotely?
  Commits are local, push and pull refer to pushing and pulling to/from the remote repository. 

Why do diffs work for source code (e.g., .R files) but not Word documents (i.e., .docx files)?
  Because changes are not recorded other than by saving a word doc.

Why is Markdown useful for GitHub repos? 
  It is easy for people to read and basically allows you to easily make a project website that can show you notes and code and product without having to download and run everything locally. 
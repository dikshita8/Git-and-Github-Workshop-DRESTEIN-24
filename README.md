# Git-and-Github-Workshop-DRESTEIN-24
NAME:  DIKSHITA.M
REGISTER NUMBER :  212222060052
DEPARTMENT :  ECE
YEAR :  THIRD YEAR
Git and GitHub Workshop Assignment  
Complete the following tasks to practice core Git commands. Answer each question and perform the associated Git operations.  
 
1. Setup and Initialize:  
- 	What command do you use to create a new directory named `git-workshop` and navigate into it?  
ANSWER: mkdir git-workshop                   cd git-workshop 
 
2. Initialize a Git Repository:  
	- 	What command initializes a Git repository in your directory?  
ANSWER: git init 
 
3. Create and Modify Files:  
- 	How do you create a new ile named `hello.txt` and add the content 'Hello, Git Workshop!' to it using a single command?  
ANSWER: echo "Hello, Git Workshop" > hello.txt 
 
4. Check the Status of Your Repository:What command displays the status of your repository?  
ANSWER: git status 
 
5. Stage and Commit Changes:  
	- 	What command stages the ile `hello.txt`?   
ANSWER: git add hello.txt 
 
- What command commits the staged ile with the message 'Add hello.txt with welcome message'?  
ANSWER: git commit -m "Add hello.txt with welcome message" 
 
6. Branching:  
	- 	What command creates a new branch named `update-content`?  
ANSWER: git branch update-content 
 
-How do you switch to the `update-content` branch?  
ANSWER: git checkout update-content 
 
7. Make Changes on the Branch:  
- 	What command would you use to append the text 'This is a simple Git assignment.' to `hello.txt`?  
ANSWER: echo "This is a simple Git assignment" >> hello.txt 
 What command stages and commits the changes with the message 'Update hello.txt with additional message'?  
ANSWER: git add hello.txt git commit -m "Update hello.txt with addi onal message" 
 
8. Merge Changes:  
-	What command switches you back to the `main` branch?  
ANSWER: git checkout main 
-	How do you merge the `update-content` branch into `main`?  
ANSWER: git merge update-content 
 
9. View Commit History:  
	- 	What command shows the commit history?  
ANSWER: git log 
 
10. Undo and Reset (Practice Safely):  
- 	If you make a change to `hello.txt` that you want to revert before committing, what command would you use?  
ANSWER: git checkout -- hello.txt 
- 	How can you reset your branch to a previous commit (optional, for advanced practice)?  
ANSWER: git reset --hard <commit-hash> 
   11.Push to a Remote Repository (Optional):  
 
	- 	What command adds a remote repository named `origin`?  
ANSWER: git remote add origin <repository-url> 
 
12.What command pushes your local `main` branch to the remote repository? 
 
ANSWER: git push origin main 


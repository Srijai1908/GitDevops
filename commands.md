# Git Commands Overview

## 1. Creating a Directory and Navigating

mkdir gitfordevops  
ls  
cd gitfordevops  
pwd  

## 2. Initializing a Git Repository

git init  

## 3. Clearing and Viewing Files

clear  
ls -a  

## 4. Creating and Viewing Files

vim hellodosto.txt   # Create and edit a file using Vim  
cat hellodosto.txt   # View the contents of the file  

## 5. Checking Git Status

git status  
ls -a  

## 6. Creating Additional Files

touch dev1.txt  
touch dev2.txt  
ls  

## 7. Staging and Committing Files

git add .  
git status  
git commit -m "Added all files"  

## 8. Removing a File

rm dev2.txt  
ls  
git status  
git restore dev2.txt  

## 9. Branching

git branch  
git checkout -b developer   # Create and switch to a new branch  

## 10. Viewing Commit Logs

git log  

## 11. Switching Branches

git switch master  
git branch  

## 12. Viewing Command History

pwd  
history  

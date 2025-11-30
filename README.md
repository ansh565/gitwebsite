# Git Bash & GitHub Hands-On Project

## Introduction
This project is a hands-on exercise to understand and practice **Git version control** and **GitHub repository management**. The objective is to demonstrate key Git operations including **repository initialization, commits, branching, merging, and conflict resolution**.

The project consists of a simple **static HTML website** named `gitwebsite`, stored locally on the Desktop. Through this project, I have:  
- Learned how to **track changes** in files using commits  
- Created and managed multiple **branches** (feature, test, bugfix, experiment)  
- Performed **merge operations** and resolved merge conflicts manually  
- Connected the local repository to a **remote GitHub repository**  
- Documented the workflow and project using **README.md**  

This project helps in building a practical understanding of version control workflows, which is essential for collaborative software development and professional coding practices.

---

## Commands Used

### Git Initialization & Commit
```bash
git init
git add .
git commit -m "Initial commit: Added project files"
```
### Branching
```bash
git branch feature
git branch test
git branch bugfix
git branch experiment
git checkout feature
git checkout test
git checkout bugfix
git checkout experiment
```
### Making Changes & Committing
```bash
git add .
git commit -m "Commit message describing the change"
```
### Merging Branches
```bash
git checkout master
git merge feature
git merge bugfix
git merge experiment
git merge test
```
### Resolving Merge Conflicts
```bash
# Edit index.html to resolve conflicts
git add index.html
git commit -m "Resolved merge conflict between master and bugfix"
```
### Remote Operations
```bash
git remote add origin https://github.com/ansh565/gitwebsite.git
git push -u origin master
git push origin feature
git push origin test
git push origin bugfix
git push origin experiment
```

---

## Screenshots
![Git Screenshot](screenshots/Screenshot%20(3855).png)



![Git Screenshot](screenshots/Screenshot%20(3856).png)



![Git Screenshot](screenshots/Screenshot%20(3857).png)



![Git Screenshot](screenshots/Screenshot%20(3839).png)



![Git Screenshot](screenshots/Screenshot%20(3872).png)



![Git Screenshot](screenshots/Screenshot%20(3857).png)



![Git Screenshot](screenshots/Screenshot%20(3863).png)

---

## Challenges

- Understanding merge conflicts and how to resolve them manually in the code

- Connecting Git Bash to GitHub account for the first time

- Pushing multiple branches while maintaining clean commit history

---

## Conclusion

This project provided valuable hands-on experience with Git version control and GitHub repository management. Through practical implementation, it helped in understanding how to initialize a repository, track changes, create meaningful commits, and manage multiple branches efficiently. The use of branching and merging operations improved clarity on how different features and fixes can be developed independently.

Additionally, the project demonstrated how merge conflicts occur and how they can be resolved manually, which is an important skill in real-world collaborative development. Working with a remote GitHub repository enhanced understanding of pushing, pulling, and maintaining synchronization between local and remote repositories. Overall, this project strengthened practical knowledge of version control systems and highlighted the importance of proper documentation and version control practices in collaborative software development.




*  Create your own git repository

* Create your first repository on github ------ if want guidance then please follow [Github Repository creation](gitpracticerules.md)

#### Setup git locally

* Install Git [Download here](https://git-scm.com/downloads?utm_source=chatgpt.com) or follow the git practice rules markdown file
* Create a folder on your computer → ​**introtogithub**​.
* Open the folder in ​**VS Code**​.
* Open the **terminal** in VS Code.

##### Intialize Git

`git init`

##### Create files in the current folder

* index.html
* Readme.md
* note.txt

##### First Commit & Push

* After completing the above steps follow the below commands to get your first push on github
  * git add . ( Here dot means select all the files in the root)
  * If you want to select any particular file then git add index.html  || git add note.txt
  * `git commit -m "First commit"`
  * `git branch -M main`

```git
git commit -m "First commit"
git branch -M main       # Rename branch to main
git remote add origin <your_repo_link>
git push -u origin main  # Push to GitHub
```

*  git remote add origin [https://github.com/PriyanshuChourasia/gitresource.git](https://github.com/PriyanshuChourasia/gitresource.git) ---- Write your own github repo link

```
git remote add origin https://github.com/YourUsername/gitresource.git
```



7. Clone a Repository.
8. Create a new branch and make changes to that particular branch and commit and push
9. Create a Pull request to merge the feature branch you created to main branch


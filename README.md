# use-git-to-github
Repo ini untuk keperluan tutorial cara pakai git to github by kumpul4semut
# Command
[] => for changed


- for inisal this folder to git
```
git init [name folder]
```
- to add to working area all changed
```
git add .
```
- add for spesifict file
```
git add [name file]
```
- commit
```
git commint -m "[input message]"
```
- check canged added not to working
```
git status
```
- clone public repo
```
git clone [url repositori]
```
- clone private
```
git clone https://username@[url repo]
```
- next input username & password for upload
```
git push [remote_name] [branch_github]
ex git push origin master
```
- to update local from github
```
git pull origin master
```
- see log all commit
```
git log
```
- create new branch
```
git checkout -b [new_branch]
```
- move branch
```
git checkout [name_branch]
```
- add branch to master
```
git checkout master
git merge [name_branch
````
- delete branch
```
git branch -d [name_branch]
```
- see all branch
```
git branch
```
- graph git
```
 alias graph="git log --all --decorate --oneline --graph"
```
- update origin remote
```
git fetch [name_remote]
```
- merge remote
```
git merge [remote_name/name_branch]
```
- delete branch on github use git
```
git push origin --delete [branch_name_do_delete]
```
- other merge use gi rebase
```
git rebase [branch_name]
```
-gitignore untuk mengabaikan file yg tidak mau di pantau git
```
Creare file .gitignore
```
-fix git ignore not work
```
git rm -r --cached .

git add .

git commit -m "fixing .gitignore"
```
-git error: failed to push some refs to
```
git pull --rebase
```

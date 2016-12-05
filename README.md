# carryon

carry on stury

### basic command 

~~~
git status
git add README.md

git diff
git commit -m "this is comment"
git rm xxx
git push

git mv README.md README
git log
~~~

### 取消

~~~
git commit --amend
git commit -m " test amend"
git add somefile
git commit --amend

git add *

git status

**git reset HEAD README.md**

git status

~~~

### REMOTE

~~~
git remote -v
git remote add ph https://github.com/gavincn/carryon
git remote rm ph
git remote add pb https://github.com/gavincn/carryon


//default remote branch name is origin
git push origin master
git remote show origin
~~~

### alias

~~~
git config --global alias.co checkout
git config --global alias.st status
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.last 'log -l HEAD'
~~~

### branch br

~~~
git br testbr
git co testbr

~~~

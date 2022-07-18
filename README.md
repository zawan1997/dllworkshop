# dllworkshop

### maven commands
1. mvn compile
2. mvn package
3. mvn clean package
4. mvn clean
5. mvn clean package spring-boot:run
6. mvn spring-boot:run

### Git commands
1. git init

2. git remote add origin https://github.com/zawan1997/projectname.git

3. git add *

4. git commit -m "message"

5. git push origin master 

to push and update, do from step 3 

If want to pull from a specific location:

git pull <repo name>

git branch -a to see everything

git branch -delete <branch name> to delete a local branch

git remote rm origin <to delete origin>

to checkout to develop branch before going to master
git checkout -b develop master
git add* (now its in develop branch)
git commit -m "develop branch add"
git push -u origin develop (push to remote git develop branch)

after finishin, merge back to master 
git checkout master <to go into master and to make it default>
git merge develop <to update master with things from develop>
git push -u origin master <push to remote master>

if did work in master then now want to pull to develop
git checkout develop
git merge master
git push -u origin develop

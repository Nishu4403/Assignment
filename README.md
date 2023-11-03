First I created a new repository in github
Then i created a new folder in my local system.
Inside my folder I opened git bash where i executed these commands

git init 

git remote add origin "https://github.com/Nishu4403/Assignment.git" 

notepad sample.txt 
(here I added these contents to the file)
Hi
I am Nishad Babu Sulikeri 
I am from Bangalore

git add . 

git commit -m "added my first commit in master branch" 

git push origin master

git branch feature-branch

git checkout feature-branch

notepad sample.txt
(here I added these contents to the file)
I study at Presidency University
I am a BTech student

git add .

git commit -m "my first commit in feature branch"

git push origin feature-branch

git checkout master

git merge feature-branch

git push origin master
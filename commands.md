#Directory & File Management (Linux)

mkdir git-for-devops
cd git-for-devops
pwd
ls
ls -l
ls -a

#File Creation & Editing

vim hello-dosto.txt
cat hello-dosto.txt
rm hello-dosto.txt
touch nibba.txt nibbi.txt
touch nibbu.txt
touch tamana.txt

#Initialize Git Repository

git init

#Git Repository Status

git status

#Add Files to Staging Area

git add nibba.txt
git add nibbi.txt
git add nibbu.txt
git add tamana.txt

#Commit Changes

git commit -m "adding nibba nibbi"
git commit -m "nibbi.txt"
git commit -m "added new changes to nibbi"
git commit -m "nibba.txt"
git commit -m "added nibbu"
git commit -m "added tamana"

#Restore Deleted File

git restore nibbi.txt

#Configure Git User

git config --global user.name "jhamanitamana-beep"
git config --global user.email "jhamanitamana@gmail.com
"

#View Commit History

git log

#Branch Management
View Branches

git branch

#Create New Branch

git checkout -b dev
git checkout -b devops

#Switch Branch

git checkout dev
git checkout devops
git checkout master

#Working with Files in Branches

vim nibbi.txt
vim nibba.txt
rm nibbitxt

#Verify Files

ls

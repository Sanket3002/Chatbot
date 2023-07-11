To Configure version of git in device : git --version (To check installed git version)

set username to git : git config --global user.name "sanket jojan"

set email to git : git congfig --global user.email "mailtosanketjojan@gmail.com"

to check username & email of git: cat ~/.gitconfig 

to make directory : mkdir "dir_name"

to clone repository from github to local machine : git clone "HTTP link of code" (PS: Don't use double quotation mark)

Open the path in VS code : code .

to check the status of cloned repository : git status

to check the difference between previous file anf modified file : git diff filename.extension

to add the modified file : git add filename.extension

to commit the changes : git commit -m "Message if any"
PS:  git add filename.extension (to save the modification done in file) the git commit to commit the change.(add-> commit)

to check the commit : git log --oneline

(HEAD -> main) means git head is pointing to main
(origin/main, origin/HEAD) -> (git,github) // before pushing files in github but commit the file in git the git log shows above message that git pointing towards the main(modefied one) and gtihub is (pointing towrds the previous file).

to push the commit from git to github : git push origin main

to pull the file from github : git pull origin main

to checkout the previous commit code : git checkout hash (hash is obtain by doing git log --oneline)

to check the current branch : git branch

to go back to main : git checkout main

Branch : branch is same as main repository but the user can modify it as per and it won't affect it on main

to create new branch : git checkout -b NewBricks







you have to know about 
git push origin main
git pull origin main












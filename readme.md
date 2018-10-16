This project addresses the "Festival Internacional de la Cultura Cerámica"

Git tutorial:

Create an user in git.
Copy the path of the proyect: https://github.com/hectorodriguezsoto/ficc
In the correct path in your local: git clone https://github.com/hectorodriguezsoto/ficc
//you are in the branch: master
git status
//change branch
git checkout develop
//get all the changes
git pull
//Create new branch
git checkout -b "feature/add_new_functionality"
Make the several changes in the proyect and:
//check the files that you added or changed
git status
//add all the files
git add .
//or discard the file that you don't want to add to the proyect
git checkout "file"
//give a description for this addition
git commit -m "Added new functionality"
//Push the code
git push origin "feature/add_new_functionality"

If you have been making changes at the same time than other person: git pull origin develop --rebaseadd

In github make a PR and compare the code. I will be checking the code and added it to develop.
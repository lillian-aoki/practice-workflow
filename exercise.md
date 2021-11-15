## Instructions for the GitHub exercises.

### Fork and clone workflow

1. Fork this repository (click on the Fork button in the upper right). 
2. From your fork on GitHub, clone the repo to your local machine: `git clone <URL FROM GITHUB>`  
Be sure to choose a sensible place in your filesystem to save the local repo. 
5. Create a new branch with the name "exercise-YOURNAME" : `git checkout -b <exercise-YOURNAME>`
6. Create a text file with the title "YOURNAME.txt": `touch YOURNAME.txt`
7. Add some text to the file YOURNAME.txt, e.g. using echo: `echo Some demo text >> YOURNAME.txt`
8. Check the status of your repo (`git status`), then stage your changes (`git add YOURNAME.txt`) and  
commit the changes (`git commit -m <commit message>`).  
9. Push your changes to your forked remote: `git push`
10. On GitHub, initiate a pull request to merge your changes with the source repo.
11. Identify the base repo (what you want to update) and head repo (where the updates come from), and  
add a title and short description to the pull request.

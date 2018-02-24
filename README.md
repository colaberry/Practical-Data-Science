# Practical-Data-Science


## Git Workflow
* Before working on a lab, checkout a new branch with $git checkout -b
* Make as many commits as you want on the branch with $git commit -a -m "explain your work"
* Push to remote with the command: $git push --set-upstream origin
* Put in a Pull Request on github and request a review.
* Post review, make changes and checkin again for review.
* Once you get a green signal with RTM as marked by reviewer (Ready To Merge), then you can merge to Master
* Never push anything to master directly without peer review.
## Merging to master
* checkout master with command : git checkout master
* Pull the lastest with command: git pull
* checkout branch that you wish to merge with command: git checkout branch
* git rebase -i master
* git checkout master
* git merge --ff-only

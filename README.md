Learning how to make commits.

# A typical git workflow involves creating branches locally and then passing them to the remote. 

# create the repo remotely
git clone <URL>

# create a branch locally
git checkout <branch>
git checkout -b <new branch>
git add ...; git commit -m "..." (several times, commit early and often)
git push --set-upstream origin <new branch>
git pull [origin <new branch>]

# alternatively, create a new branch remotely
using the GitHub UI to create <branch>
git fetch --all 
git checkout <branch>
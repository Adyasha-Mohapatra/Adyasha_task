**GitHub Flow**

1. ***CREATE A REPOSITORY***:
Login to the GitHub web console  > Click on the tab “New repository” > Give a name to your repository.
2. ***CLONING THE REPOSITORY*** :
In order to clone the repo, in the GitHub web console  > Click button named "clone or download" and copy the link > Go to the VSC terminal and
use the git command in order to clone it. The Git command is git clone <url>
3. ***BRANCHING*** :
In order to create a new branch just type "git checkout -b <branch name>. Now you are in a new branch. You can make changes in the new branch.
4. ***ADDING NEW FILES*** :
In order to add files first we have to use the basic linux command in order to create the files. So here I will be adding 2 files  i.e readme.txt and calc.py. Here I am using the linux command i.e. “touch readme.txt” then hit enter and again type “touch calc.py” and hit enter. Now both the files are created. But these files and not recognized by git. So we need to use the git command in order to make it recognised by git. So the git command would be “git add -A”. This will add bothe files together. If you want, you can also do it separately by typing “git add <file name>”.
5. ***COMMIT*** :
Now that we are in the staging area, we can commit the changes. Commit means we are going to save the changes. In order to commit we have to use the git command i.e. “git commit -m <commitmessage>”. Here my commit message is “Initial_commit” and once you hit enter it will be commited.
6. ***PUSH***:
Now that we have made the commit, its time to push the changes to the remote repo. So in order to do that type “git push origin <featurebranchname>”. If you now go to the console you can see the changes that you made will come up.
7. ***PULL REQUEST***:
Now that we have pushed everything successfully. Its time to “pull request” so that others who are working on the same project can see the changes we made. So you need to click on “create pull request” tab. You can give a name to your pull request. And again click on the tab that says "create pull request".
8. ***MERGE PULL REQUEST***:
Now as it has got no conflicts, you can merge the pull request in the master branch by just clicking on “Merge pull request” tab. Now our merging has been done successfully. If you want you can delete the feature branch safely.
9. ***DELETE THE FEATURE BRANCH***
Once we merge it, we can delete the feature granch.

**STEPS TO SET THE MESSAGE OF THE DAY**
1. Open your Turbot Console in a browser window.
2. Login as a Cluster Administrator.
3. Browse to ADMIN, then Options.
4. In the left menu, navigate to Turbot Options, Console.
5. Set Message of the Day and click Customize. HTML is permitted.

**STEPS TO REMOVE THE NESSAGE OF THE DAY**
1. Open your Turbot Console in a browser window.
2. Login as a Cluster Administrator.
3. Browse to ADMIN, then Options.
4. In the left menu, navigate to Turbot Options, Console.
5. For Message of the Day click Remove.

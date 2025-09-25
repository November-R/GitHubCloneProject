**INTRODUCTION**

This project reinforces the concept of remote repositories and introduces you to managing and updating project content after cloning it from GitHub.

**STEPS**

*1.Create a New Repository o Github*
-Log into your github account
-Navigate to the repository creation page
-Name your repository
-Choose visibility as public
-Click Create repository

*2.Clone the Repository*
-Copy the htpps link of the created repo
-open your terminal or command prompt
-Choose a suitable directory to clone the repo
-Execute the clone command:

``git clone <Repos_url>``

-Replace <repo_url> with the url you copied from github


*3.Add New Content*
-Navigate into the cloned repo directory
-Execute the command:

``cd <Repo_name>``

-Make the necessary changes needed


*4.Commit your chaned*
-Add the new file to the staging area using
-Execute the command:

``git add .``

-commit the changes to you local repo
-Execute the command:

``git commit -m "a descriptive message of your changes"``

*5.Push Your Changes*
-Push your changes to the github repo
-Execute the command:

``git push origin <your_branch>``

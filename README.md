Modification in feature-greeting branch.
**INTRODUCTION**

This project reinforces the concept of remote repositories and introduces you to managing and updating project content after cloning it from GitHub.

**STEPS**

*1.Create a New Repository o Github*<br>
-Log into your github account<br>
-Navigate to the repository creation page<br>
-Name your repository<br>
-Choose visibility as public<br>
-Click Create repository<br>

*2.Clone the Repository*<br>
-Copy the htpps link of the created repo<br>
-open your terminal or command prompt<br>
-Choose a suitable directory to clone the repo<br>
-Execute the clone command:<br>

``git clone <Repos_url>``

-Replace <repo_url> with the url you copied from github<br>


*3.Add New Content*<br>
-Navigate into the cloned repo directory<br>
-Execute the command:<br>

``cd <Repo_name>``

-Make the necessary changes needed<br>


*4.Commit your chaned*<br>
-Add the new file to the staging area using<br>
-Execute the command:<br>

``git add .``

-commit the changes to you local repo<br>
-Execute the command:<br>

``git commit -m "a descriptive message of your changes"``

*5.Push Your Changes*<br>
-Push your changes to the github repo<br>
-Execute the command:<br>

``git push origin <your_branch>``

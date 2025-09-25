Modification in feature-greeting branch.
**INTRODUCTION**

This project reinforces the concept of remote repositories and introduces you to managing and updating project content after cloning it from GitHub.

**STEPS TO CLONE AND EDIT A REPO**

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




**Branching, Making Changes, and Resolving Merge Conflicts**<br>

The Objective is to : create a branch for feature development, merge branches, and resolve merge conflicts.<br>

*Skills*:<br>

-Branching and navigating between branches<br>
-Making changes in different branches and committing those changes<br>
-Merging branches and resolving conflicts<br>


*Steps:*<br>

*Initial Setup:<br>*

-Use the cleaned repo repository we have created above.<br>
-Create a README.md file if you don’t already have one.<br>
-Make sure you have some content in the README.md.<br>

-Clone the repository to your local machine if you haven’t already:<br>
 ``git clone <REPOSITORY-URL>``

-Navigate into the repository’s directory:<br>
 ``cd clonedrepo``

-Create a New Branch:

-Create and switch to a new branch, name it what you want:<br>
 ``git checkout -b new_branch_name``

-add some content related to a feature, for example:

 -This is a new feature.
 -Add and commit the change:

 ``git add feature.txt``
 ``git commit -m "Add feature description"``

-Modify the README.md file by adding a new line just below the first line (Second line in the file):<br>

 -Modification in feature-greeting branch.<br>
 -Commit the change:<br>

 ``git add README.md``
 ``git commit -m "Modify README in feature-greeting branch"``

-Push the new branch to github<br>
 ``git push origin <new_branch_name>``


*Makeing Changes in the Main Branch:*<br>

-Switch back to the main branch:<br>
 ``git checkout main``
-Modify the README.md file by adding a new line just below the first line (Second line in the file):<br>

 *Modification in main branch.*
-Commit the change:

 ``git add README.md``
 ``git commit -m "Modify README in main branch"``

*Merge the Feature Branch and Resolve a Conflict:*<br>

-Attempt to merge feature-greeting into main:<br>
 ``git merge feature-greeting``

If a merge conflict occurs, open the conflicting file(s) in a text editor. Manually resolve the conflicts by editing the file to keep or integrate both sets of changes.<br>
After resolving the conflict, add the file to the staging area and commit the merge:<br>

 ``git add .``
 ``git commit -m "Description of howyou resolved the conflicts"``

*Push Changes to GitHub:*<br>
-Push the updated main branch, including the merged feature and resolved conflict, to GitHub:<br>

 ``git push origin main``
Expected Outcome:

*You will have successfully created a new feature branch, made changes in both the feature-greeting and main branches, and resolved a merge conflict resulting from attempting to merge these branches. Your clonedReponame repository on GitHub will reflect these changes and the merge resolution.*

Notes:

This project simulates a collaborative scenario where changes made in different branches can lead to conflicts. It helps you to manage branches, navigate merge conflicts, and maintain a clean project history.

Modification in main branch

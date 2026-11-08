\# Answers



\## Task 1



(a) git commit saves changes to the local repository on my computer. git push uploads those saved commits to the remote repository on GitHub. Commit is a local save; push is the upload to the internet.



(b) origin is the default nickname Git gives to the remote repository you cloned from. It represents the URL (in this case, my GitHub repository).



(c) There are two complete copies of the project history: one on my local computer (the folder `\~/projects/week5-github`) and one on GitHub's server (the remote repository).








## Task 2

(a) A README is read by anyone who visits the repository — users, contributors, teachers, employers. It should answer: what the project is, how to install and run it, what files it contains, and where to find more information.

(b) If there is no license, other people legally cannot copy, modify, or distribute the code. By default all rights are reserved by the author.

(c) I chose the MIT license because it is simple and permissive, allowing others to use and modify the code freely as long as they keep the attribution.







## Task 3

(a) A pull request is a request to merge a branch into another branch (usually main), with a page for review and discussion. Teams use them instead of pushing directly to main so that changes can be reviewed, tested, and discussed before they reach the main codebase, reducing the risk of breaking things.

(b) In step 5, git pull downloaded the merged changes from GitHub and merged them into my local main branch. The difference from git fetch is that git fetch only downloads remote changes without modifying my local branch, while git pull fetches AND merges them into my current branch.




## Task 4

(Note: As instructed, I completed this task alone by using a branch.)

(a) A fork is a copy of someone else's repository created in your own GitHub account. A clone is a copy of a repository on your local machine. Forking happens on GitHub; cloning happens with git clone. You fork to get your own writable copy of someone else's project, then clone your fork to work on it locally.

(b) You open a pull request instead of pushing straight into the partner's repository because you do not have write access to their repository. A pull request asks the owner to review and merge your changes, which keeps their main branch safe and lets them give feedback.

(c) I learned that reviewing code line by line helps catch small issues and gives useful feedback. Writing a review comment made me think about how to give friendly, constructive suggestions.
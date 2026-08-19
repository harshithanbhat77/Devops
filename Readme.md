----HERE IS THE DEVOPS DOCUMENTATION----

1. What is Git?
Git is a version-control system used to track changes in code.

2. Why do we need version control?
Suppose we have:

app_v1
app_v2
app_final
app_final_latest
app_final_latest2

Instead of maintaining copies like this, Git keeps the complete history of changes.


3. Git vs GitHub

Git
↓
Runs on your machine
Tracks code changes

GitHub / GitLab / Bitbucket
↓
Stores Git repositories remotely
Allows team collaboration
Pull Requests
Code Review
CI/CD


4. Understand this basic Git flow

Working Directory
      ↓
   git add
      ↓
Staging Area
      ↓
 git commit
      ↓
Local Repository
      ↓
   git push
      ↓
Remote Repository
GitHub/GitLab/Bitbucket
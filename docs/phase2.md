Problem:
git push asks for username and password.

Cause:
Repository remote configured for HTTPS.

Resolution:
Configure SSH authentication and switch remote URL:
git remote set-url origin git@github.com:/.git

Problem:
git push -u origin master
returns "error: src refspec master does not match any"

Cause:
The local branch is named "main", not "master".

Verification:
git branch

Resolution:
git push -u origin main

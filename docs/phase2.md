Problem:
git push asks for username and password.

Cause:
Repository remote configured for HTTPS.

Resolution:
Configure SSH authentication and switch remote URL:
git remote set-url origin git@github.com:/.git

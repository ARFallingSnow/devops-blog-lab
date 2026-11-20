


Common Issue: python3 -m venv .venv fails with:
"The virtual environment was not created successfully because ensurepip is not available"

Resolution:
sudo apt install python3.14-venv
Then recreate the virtual environment.

Error:
"The virtual environment was not created successfully because ensurepip is not available."

Resolution:
sudo apt install python3.14-venv

Then recreate the environment:
python3 -m venv .venv

Lesson Learned:
Ubuntu may include Python without virtual environment support packages installed.


Checkpoint D
Installed and verified Git.

Key Concepts:

Git manages versions of files.
GitHub hosts Git repositories remotely.
Virtual environments should not be committed.
.gitignore prevents unnecessary files from entering source control.
Created:

.gitignore

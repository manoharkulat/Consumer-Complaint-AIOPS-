
## Basic git commands

for Cloning Source code from repo
```
git clone <https://github.com/manoharkulat/Consumer-Complaint-AIOPS-.git>
```

To add file to stageing area or to allow files to be tracked by git
```
git add <fileName>
```

To perform commit
```
git commit -m "message abt your changes"
```

rename current branch to main branch 
```
git branch -M main
```

To list the branch name
```
git branch
```

To check remote branch url and variable name
```
git remote -v
```

To send changes to remote branch
```
git push <remote_branch_variable> <branch Name>
```

To remove file from staging area
```
git rm --cached <fileName>
```
### Conda environment commands

To create conda run time environment for project
```
conda create -p venv python==3.7 -y
```
To activate conda environment for project
```
conda activate <./dir_name>
```
### To create requirements.txt file
```
pip freeze > requirements.txt
```
### To install jupyter lab
```
pip install jupyter lab
```
### bash command to create dir
```
mkdir <dir_name>
```
# HARMEET-SINGH
git config --global user.name "HARMEET-SINGH"
git config --global user.email "hsingh1_be24@thapar.edu"
mkdir my_project
cd my_project
git init
echo "Hello Git" > file.txt
git status
git add file.txt
git commit -m "Initial commit with file.txt"
git branch new_feature
git checkout new_feature
git checkout main
git merge new_feature
git remote add origin https://github.com/HARMEET-SINGH/my_project.git
git push -u origin main
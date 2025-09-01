cd path/to/your/class-folder
mkdir first-project
cd first-project
git init
echo # add whatever text you want > README.md
git remote add origin https://github.com/yourusername/CS3338-first-project.git
git branch main
git checkout main
git add index.html
git commit -m "Add index.html file"
git push
git pull origin main
git add index.html
git commit -m "Add final project idea"
echo https://github.com/yourusername/CS3338-first-project.git > repo-location.txt
git add repo-location.txt
git commit -m "Add repo location"
git push

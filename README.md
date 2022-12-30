# git_shtest
echo "# git_shtest" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Huijigo/git_shtest.git
git push -u origin main

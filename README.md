echo "# test_one" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/baloghib/test_one.git
git push -u origin main

git remote add origin https://github.com/baloghib/test_one.git
git branch -M main
git push -u origin main

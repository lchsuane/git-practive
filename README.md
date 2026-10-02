ssh -T git@github.com
git config --global user.name "lchsuane"
git config --global user.email "mbssdemon7@icloud.com"
git clone git@github.comn:mbssdemon7@icloud.com/git-practive.git
cd git-practive
echo "Hello, Git" > hello.txt
git status
git add hello.txt
git.commit -m "Add hello.txt"
git push

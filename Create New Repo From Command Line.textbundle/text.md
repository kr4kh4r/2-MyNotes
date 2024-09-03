Create New Repo From Command Line:

echo "# FS-Notes" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/harworrell/FS-Notes.git
git push -u origin main


Push Existing Repo From Command Line:

git remote add origin https://github.com/harworrell/FS-Notes.git
git branch -M main
git push -u origin main

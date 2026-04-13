git switch main
git pull
git switch -c feature/nombre

git add .
git commit -m "mensaje"
git push -u origin feature/nombre

git switch main
git pull
git merge feature/nombre
git push

git branch -d feature/nombre
git push origin --delete feature/nombre
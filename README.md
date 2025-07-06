#test rss

echo "# rs-school" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/finmaster-dvd/rs-school.git
git push -u origin main

Добавление всех изменений:
git add -A
git commit -m 'update: change readme text'
git push origin main
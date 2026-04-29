git init
git add .
git commit -m "test secret"
git branch -M main
git remote add origin https://github.com/harihas12345/devsec.git
git pull origin main --allow-unrelated-histories
git push -u origin main
git push -u origin main --force

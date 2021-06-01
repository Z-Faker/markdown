**Faker**
---
- git config --global url."https://github.com.cnpmjs.org/".insteadOf "https://github.com/"
- git config --global user.name "Z-Faker"
- git config --global user.email 1049356915@qq.com

---
- git branch -a
- git checkout -b develop
- git branch -a
- git add .
- git commit -m "finish markdown"
- git checkout main
- git merge develop
- git push origin main 

1️⃣ GitHub par Repository Create karo

Browser open karo

GitHub website par jao

Login karo

New repository click karo

Example:

Repository name: k8s-nginx-deployment

Options:

Public ✅

Add README (optional)

Click Create repository

2️⃣ Apne System me Folder Create karo

Terminal me:

mkdir k8s-project
cd k8s-project

Ab apni YAML file yaha rakho:

Example:

deployment.yml

Check:

ls
3️⃣ Git Initialize karo
git init

Isse folder Git repository ban jata hai.

4️⃣ File Git me Add karo
git add deployment.yml

Ya sab files add karne ke liye:

git add .

Check status:

git status
5️⃣ Commit karo
git commit -m "Added nginx deployment yaml"

Commit ka matlab:

👉 code ka snapshot save karna

6️⃣ GitHub Repository Connect karo

GitHub repo page par aapko command milegi.

Example:

git remote add origin https://github.com/username/k8s-nginx-deployment.git

Check:

git remote -v
7️⃣ Code GitHub par Push karo
git branch -M main
git push -u origin main

Ab aapka code GitHub par upload ho jayega 🎉

8️⃣ Browser me Check karo

Repository open karo:

https://github.com/username/k8s-nginx-deployment

Aapki file dikhegi:

deployment.yml

1️⃣ GitHub me Personal Access Token (PAT) create karo

GitHub login karo

Top right profile icon → Settings

Scroll down → Developer settings

Click Personal access tokens

Click Tokens (classic)

Click Generate new token

Token name example:

git-token

Expiration:

30 days or No expiration

Scopes select karo:

repo

Click Generate Token

⚠ Important: Token copy karke save kar lo (baad me nahi dikhega).

2️⃣ Terminal me push karo

Phir command run karo:

git push -u origin main

Prompt aayega:

Username:

Enter:

password: 

Enter: 

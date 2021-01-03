npm init -y
npm install json-server
touch .gitignore
echo node_modules > .gitignore
git init .
git remote add origin git@github.com:cashoefman/api-server.git
git add --all .
git commit -m "premier"
git push origin master
https://my-json-server.typicode.com/cashoefman/api-server
# catalog-service


#create a new repository on the command line
`echo "# catalog-service" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/meisallcom/catalog-service.git
git push -u origin main`


#push an existing repository from the command line

`git remote add origin https://github.com/meisallcom/catalog-service.git
git branch -M main
git push -u origin main`

#git proxy setting
`git config --global http.proxy http://127.0.0.1:51837
git config --global https.proxy https://127.0.0.1:51837`


git config --global --unset https.proxy
git config --global --unset http.proxy
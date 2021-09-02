# ShoppingList

## Electron Sample App based upon tutorial: 
 - https://www.youtube.com/watch?v=kN1Czs0m1SU

### Development environment dependencies
``` PowerShell
choco install vscode git gh nodejs -y
```

### Initial github project setup
``` PowerShell
mkdir ShoppingList
cd ShoppingList

git config --global user.email "wouterspaans@hotmail.com"
git config --global user.name "Wouter Spaans"

gh auth login
gh repo create ShoppingList

git init -b main
echo "# ShoppingList" >> README.md
git add README.md
git remote add origin https://github.com/WouterSpaans/ShoppingList.git
git commit -m "first commit"
git push -u origin main
```
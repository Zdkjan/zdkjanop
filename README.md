# zdkjanop
mkdir my-project
cd my-project
git init
echo "# My Project" > README.md
git add README.md
git commit -m "Add README file"

echo "node_modules/" > .gitignore
git add .gitignore
git commit -m "Add .gitignore to ignore node_modules"

echo "<!DOCTYPE html><html><head><title>My Project</title></head><body></body></html>" > index.html
git add index.html
git commit -m "Add index.html with basic structure"

echo "body { font-family: Arial; }" > style.css
git add style.css
git commit -m "Add basic CSS styling"

echo "console.log('Hello, World!');" > script.js
git add script.js
git commit -m "Add JavaScript console log"

###This repo is contains lists of my todos.

###Here all of my commands:


```bash
mkdir todo-list
cd todo-list
git init
touch README.md
nano README.md
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/nayeem-bd/todo-lists.git
git push --set-upstream origin master
git checkout -b feature-1
touch office-todo.txt
nano office-todo.txt
git add .
git commit -m "Add office todo"
git checkout master
git checkout -b feature-2
touch home-todo.txt
nano home-todo.txt
git add .
git commit -m "Add home todo"
git push --set-upstream origin feature-2
git checkout feature-1
git push --set-upstream origin feature-1
git checkout master
git branch -d feature-1
git push origin --delete feature-1
git branch -d feature-2
git push origin --delete feature-2
```



# git-learning-session-practice
# Git Learning Session – Practice Instructions

## 1. Create a GitHub account
Install and configure Git on your machine:  
[Guide here](https://www.atlassian.com/git/tutorials/install-git)

(Optional) Configure Git with your name and email:
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## 2. Clone this repository

This is a public repository for the practice:  
[https://github.com/jorgearaya474/git-learning-session-practice](https://github.com/jorgearaya474/git-learning-session-practice)

Clone it to your computer:
```bash
git clone https://github.com/jorgearaya474/git-learning-session-practice.git
cd git-learning-session-practice
```

## 3. Create a new branch

Create a new branch using this pattern: `test-{your_name}`

Example: `test-jorge`
```bash
git checkout -b test-yourname
# Example:
git checkout -b test-jorge
```

## 4. Create a new file

Create a new file using this pattern: `hello-world-{your_name}.txt`

Example: `hello-world-jorge.txt`
```bash
touch hello-world-yourname.txt
```

Add any content you like to the file. For example:
```
Hello World, my name is {your_name}.
```

## 5. Add your changed file(s) to Git
```bash
git add .
# or
git add hello-world-yourname.txt
```

## 6. Commit your changes
```bash
git commit -m "Add hello world file"
```

## 7. Push your branch to GitHub
```bash
git push origin test-yourname
```

## 8. Create a Pull Request and merge your changes

1. Go to the repository on GitHub.
2. You will see a **"Compare & Pull Request"** button.
3. Create the Pull Request.
4. Merge your changes.

---

⭐ *If you get stuck, don't worry, this is part of the learning process!*
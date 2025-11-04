# Short Response Questions

**1. If you are collaborating with classmate what is the first thing that each of the team members needs to do? Why is it important to do this step?**

**Hint: After this step each team member would have diverged from the main branch!**

1. **Answer :** Each team member should create their own branch by using command `git branch <branch_name>` and switch to the branch by using command `git checkout <branch_name>` It is important because it can let every collaborator independently doing their work without change the content in main branch. It also help to avoid conflict from other's code. It make collaboration more smooth.

---

**2. Why do developers use branches?**

2. **Answer:** Developers use branches during collaborating and also use the branches because the changes in branch will not permanent changes to main so doing work in branch will without affecting main. It can let developer work more easier and safer.

---

**3. What is git? What is github? How does git and github work together?**

3. **Answer:** Git is a command line tool that allows you to track and manage the changed in your code, and it's the Distributed Version Control System. GitHub is a cloud based website where you can store your Git projects in the cloud and share them with others. Also it's user friendly. They work together because Git manages your project and handles the version control on your computer, and GitHub helps you save the project more easier and more friendly to user. It both help developer work more easier.

---

**What is wrong with the following command sequence? What should be the corrcet command sequence?**

```
git commit -m "saving work"
git add .
git push
```

4. **Answer:** The command sequence is wrong because `git add .` should come first so you can stage your change then use git commit -m "saving work" to commit the change. The command was write in opposite.

**Correct Command Sequence:**
```
git add .
git commit -m "saving work"
git push
```
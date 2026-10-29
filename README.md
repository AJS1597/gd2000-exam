# GD 2000 Midterm Exam

Complete the following steps, being especially careful to do the git workflow
steps with manual commands.

This is not an AI task nor a research task. You shouldn't be using either local
AI tools or search engines. You should know how to do these things.

Grading for this exam will be 50% for git / direction following and 50% for
giving good answers to the questions.

**Setup**

Make sure the `gh` tool is installed on the lab computer.

If not, you will need to [follow these directions](
https://github.com/cli/cli/blob/trunk/docs/install_linux.md#debian)

Then do `gh auth login` and `gh auth setup-git`.

## 1. Fork this repository

Press "Fork" on GitHub. You now have your own copy, under your own account.

## 2. Clone your fork

Clone *your* fork, not the original. Use `git clone` or `gh repo clone`.

## 3. Run some commands.

In the directory for your local clone, run: 

```
ps -ef > procs.txt
find . > find1.txt
```

## 3. Answer the questions

Fill in `exam-questions.md`. Six questions, a few sentences each.

## 4. Commit some of it, not all of it

Add and commit this stuff

- find1.txt
- exam-questions.md

Don't add or commit this:

- procs.txt

## 5. Push

    git push

## 6. Submit

Go to the assignment on Inkfish, open the "Clone Git Repo" tab, and paste the
URL of *your* fork:

    https://github.com/<your-username>/gd2000-exam

Inkfish clones whatever is on GitHub at that URL, so make sure you pushed to
the branch you normally see on the page (usually `main`).


# exercise-with-github

## what is it?

This is a random application to study some use cases for git functionalities such as rebase

```bash
git init
```

This code runned in a project initialize the repo. It will create a folder in the project named “.git”

```bash
git clone <repourl>
```

This command will clone the repo in your target folder

```bash
git add *
```

This command will put every edited file in stage ready for the commit

```bash
git add <filename>
```

This command will put a specific file in the stage

```bash
git commit -m "feat: add message to this commit"
```

With this code a commit will execute with the message in the quote

```bash
git push
```

push the code in the origin

```bash
git status
```

To check the current repo status considering all the branches, edited files and files ready to be pushed 

```bash
git log
```

See the commit history

```bash
git --no-pager diff
```

To see the difference between the origin and the edited files. The —no-pager atttributed block git to use the pager to list all the edits. If you don’t use it remember to press on “q” to use again the cmd instance

<aside>
📍

FROM CHATGPT: 

When you run **`git diff`**, Git opens the diff output in a **pager**, usually **`less`** (or sometimes `more`).

This *locks* your terminal until you exit the pager — it **isn't frozen**, it’s just waiting for you to quit the diff view.

</aside>
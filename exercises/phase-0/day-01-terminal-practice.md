# Phase 0 — Day 1: Terminal Practice

## 1. Objective

Practice navigating Ubuntu, creating directories, creating files, and understanding the terminal commands used in this course.

## 2. Exercise A — Check the Current Directory

Run:

```bash
pwd
```

**Question:** What does `pwd` display?

My answer:

TODO: Write your answer.

## 3. Exercise B — List Files and Directories

Run:

```bash
ls
ls -la
```

**Questions:**
1. What does `ls` do?
2. What additional information does `ls -la` show?

My answers:

TODO: Write your answers.

## 4. Exercise C — Create the Course Workspace

Run:

```bash
mkdir -p ~/fullstack-mastery/phase-0/day-01
```

Enter the directory:

```bash
cd ~/fullstack-mastery/phase-0/day-01
```

Verify:

```bash
pwd
```

**Questions:**
1. What does `mkdir` do?
2. What does `-p` mean?
3. What does `cd` do?
4. What does `~` represent?

My answers:

TODO: Write your answers.

## 5. Exercise D — Create a Notes File

Run:

```bash
touch notes.md
ls
```

Expected result: `notes.md` appears in the directory listing.

Open it in VS Code:

```bash
code notes.md
```

If the `code` command is unavailable, open VS Code manually and select the file.

Add this content:

```markdown
# My First Web Development Notes

## Frontend
The part of the application users see and interact with.

## Backend
The part that processes requests and applies application logic.

## Database
The system used to store and retrieve data.
```

Save the file.

## 6. Exercise E — Understand a Web Request

If an internet connection is available, run:

```bash
curl -I https://example.com
```

Observe the response headers.

**Questions:**
1. What does `curl` do?
2. What does `-I` request?
3. What does HTTP status `200` mean if it appears?
4. Did the command succeed? If not, what exact error appeared?

My answers:

TODO: Write your answers.

Note: Output can differ depending on the server and network. If `curl` is not installed, record that fact rather than installing packages without checking first.

## 7. Exercise F — Git Repository Check

Return to the course repository:

```bash
cd ~/fullstack-mastery
```

Check the status:

```bash
git status
```

After you have edited and saved your notes, stage and commit the new files:

```bash
git add notes/phase-0/day-01-web-foundations.md
git add exercises/phase-0/day-01-terminal-practice.md
git commit -m "docs: add phase 0 day 1 notes and exercises"
git push
```

If Git reports that there is nothing to commit, inspect `git status` and confirm that the files are saved in the repository you intended.

## 8. Troubleshooting Notes

### Error: No such file or directory

Possible cause: The directory does not exist or the path is incorrect.

Try:

```bash
pwd
ls
```

Check the current location before running `cd` again.

### Error: code: command not found

Possible cause: The VS Code command-line launcher is not available in the shell.

Solution: Open VS Code through the Ubuntu applications menu and use File → Open Folder.

### Error: not a git repository

Possible cause: You are outside the Git repository.

Try:

```bash
cd ~/fullstack-mastery
git status
```

If your repository is stored elsewhere, navigate to its actual path.

### Error: failed to push

Possible causes include authentication failure, an incorrect remote URL, or remote history differences.

Inspect:

```bash
git remote -v
git status
git log --oneline -5
```

Do not force-push or overwrite remote history without understanding the cause.

## 9. Completion Checklist

- [ ] I checked my current directory.
- [ ] I listed files and directories.
- [ ] I created and entered the practice directory.
- [ ] I created and edited `notes.md`.
- [ ] I attempted the HTTP request.
- [ ] I recorded any error messages.
- [ ] I committed the two course files.
- [ ] I pushed my changes to GitHub.

## 10. Reflection

**What did I learn today?**

TODO: Write your answer.

**What was difficult?**

TODO: Write your answer.

**What do I need help understanding?**

TODO: Write your answer.

**Status:** In progress
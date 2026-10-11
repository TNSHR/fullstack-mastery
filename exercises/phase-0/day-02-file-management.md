# Phase 0 — Day 2: File Management Practice

## Objective

Practice basic Linux file and directory operations safely.

## Exercise 1 — Inspect Your Repository

Navigate to the repository:

```bash
cd ~/fullstack-mastery
```

Run:

```bash
pwd
ls
ls -la
```

Record the output or summarize what you observed.

**Questions:**
1. What is your current directory?
2. Which files are visible?
3. Did `ls -la` reveal any hidden entries?

My answers:

TODO: Complete after practice.

## Exercise 2 — Create a Practice Workspace

Run:

```bash
mkdir -p ~/terminal-practice/day-02
cd ~/terminal-practice/day-02
```

Verify:

```bash
pwd
```

**Questions:**
1. Why did we use `mkdir -p`?
2. Why are we practicing outside the course repository?

My answers:

TODO: Complete after practice.

## Exercise 3 — Create Files and a Directory

Run:

```bash
touch first.txt second.txt
mkdir documents
ls -la
```

Expected result:
- `first.txt`
- `second.txt`
- `documents/`

**Task:** Explain the purpose of `touch` and `mkdir`.

My answer:

TODO: Complete after practice.

## Exercise 4 — Write and Append Text

Run:

```bash
echo "Learning Linux terminal" > first.txt
echo "Day 2 practice" >> first.txt
cat first.txt
```

Expected content:

```text
Learning Linux terminal
Day 2 practice
```

**Questions:**
1. What does `>` do?
2. What does `>>` do?
3. Why is it important to understand the difference?

My answers:

TODO: Complete after practice.

## Exercise 5 — Copy a File

Run:

```bash
cp first.txt documents/first-copy.txt
cat documents/first-copy.txt
```

Verify that `first.txt` still exists.

**Question:** Does copying remove the original file?

My answer:

TODO: Complete after practice.

## Exercise 6 — Rename and Move a File

Run:

```bash
mv second.txt renamed.txt
mv renamed.txt documents/
```

Inspect the structure:

```bash
ls
ls documents
```

Expected structure:

```text
day-02/
├── first.txt
└── documents/
    ├── first-copy.txt
    └── renamed.txt
```

**Questions:**
1. How did `mv` rename the file?
2. How did `mv` move the file?
3. What is the difference between the two operations?

My answers:

TODO: Complete after practice.

## Exercise 7 — Navigate Between Directories

Run one command at a time:

```bash
pwd
cd documents
pwd
cd ..
pwd
cd ~
pwd
```

Before running each `cd` command, predict the resulting directory.

Record your observations:

TODO: Complete after practice.

## Exercise 8 — Debugging Challenge

Try these commands:

```bash
cd ~/terminal-practice/day-02
cd missing-folder
```

The second command should fail if the directory does not exist.

Now investigate:

```bash
pwd
ls -la
```

**Questions:**
1. Why did the command fail?
2. Which commands helped you investigate?
3. What would you do before attempting a fix?

My answers:

TODO: Complete after practice.

## Exercise 9 — Repository File Check

Return to your course repository:

```bash
cd ~/fullstack-mastery
```

Confirm that these files exist:

- `notes/phase-0/day-01-web-foundations.md`
- `exercises/phase-0/day-01-terminal-practice.md`
- `notes/phase-0/day-02-terminal-basics.md`
- `exercises/phase-0/day-02-file-management.md`

Use `ls` or `cat` to inspect the files.

## Completion Checklist

- [ ] I inspected my repository.
- [ ] I created the practice workspace.
- [ ] I created files and directories.
- [ ] I wrote and appended text.
- [ ] I copied a file.
- [ ] I renamed and moved a file.
- [ ] I navigated between directories.
- [ ] I diagnosed a missing-directory error.
- [ ] I completed the written questions.

## Reflection

**What did I learn?**

TODO: Write your answer.

**What was difficult?**

TODO: Write your answer.

**What do I need to practice again?**

TODO: Write your answer.

**Status:** In progress
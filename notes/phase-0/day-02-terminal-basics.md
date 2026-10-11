# Phase 0 — Day 2: Files, Folders, Paths and Terminal Basics

## 1. Learning Objectives

By the end of this lesson, I should be able to:

- Understand the Linux filesystem hierarchy.
- Differentiate absolute and relative paths.
- Explain the purpose of `~`, `.`, and `..`.
- Navigate directories using `cd`.
- List files using `ls`.
- Create files and directories.
- Read, copy, move, and rename files.
- Understand the difference between `>` and `>>`.
- Diagnose common terminal errors.

## 2. Linux Filesystem

Linux organizes files and directories in a hierarchical structure.

- `/` — filesystem root.
- `/home` — usually contains users' home directories.
- `~` — shorthand for the current user's home directory.
- `.` — current directory.
- `..` — parent directory.
- `/tmp` — temporary-file directory.

Example:

`/home/shrinath/fullstack-mastery/README.md`

Here, `README.md` is inside `fullstack-mastery`, which is inside the user's home directory.

## 3. Absolute and Relative Paths

### Absolute path

An absolute path starts from `/`.

Example:

`/home/shrinath/fullstack-mastery/README.md`

### Relative path

A relative path is interpreted from the current directory.

If the current directory is `fullstack-mastery`, the relative path is:

`README.md`

Example of a relative path to the Day 1 notes:

`notes/phase-0/day-01-web-foundations.md`

## 4. Essential Commands

| Command | Purpose |
|---|---|
| `pwd` | Print current directory |
| `ls` | List directory contents |
| `ls -la` | Show hidden entries and detailed information |
| `cd DIR` | Change directory |
| `cd ..` | Move to the parent directory |
| `cd ~` | Move to the home directory |
| `mkdir DIR` | Create a directory |
| `mkdir -p PATH` | Create parent directories as needed |
| `touch FILE` | Create an empty file if absent; otherwise update its timestamp |
| `cat FILE` | Display file contents |
| `cp SOURCE DEST` | Copy a file |
| `mv SOURCE DEST` | Move or rename a file |
| `file FILE` | Identify a file's type |

## 5. Creating and Inspecting Files

Create a directory:

```bash
mkdir practice
```

Create a nested directory structure:

```bash
mkdir -p exercises/phase-0/day-02
```

Create a file:

```bash
touch notes.md
```

Inspect the current directory:

```bash
pwd
ls -la
```

Read a file:

```bash
cat notes.md
```

## 6. Writing and Appending Text

Write or replace file content:

```bash
echo "First line" > sample.txt
```

Append content:

```bash
echo "Second line" >> sample.txt
```

Read the file:

```bash
cat sample.txt
```

Important:
- `>` replaces existing content.
- `>>` appends to existing content.
- Inspect important files before modifying them.

## 7. Copying, Moving and Renaming

Copy:

```bash
cp sample.txt sample-copy.txt
```

Move into a directory:

```bash
mv sample-copy.txt documents/
```

Rename:

```bash
mv sample.txt renamed.txt
```

The `mv` command can move a file or rename it, depending on the destination.

## 8. Linux Filename Rules

- Linux filenames are case-sensitive.
- Spaces in filenames require appropriate quoting or escaping.
- Hidden files commonly begin with a dot, such as `.gitignore`.
- File extensions help identify intended formats but do not guarantee actual file contents.
- Use descriptive names and consistent directory organization.

## 9. Common Errors

### No such file or directory

Possible causes:
- Incorrect path.
- Typo in the filename.
- Directory does not exist.
- Wrong current directory.

Diagnosis:

```bash
pwd
ls -la
```

### File created in the wrong directory

Check the current directory using `pwd` before creating or moving files.

### Content unexpectedly overwritten

The `>` operator replaces existing content. Use `>>` to append when appropriate.

### Permission denied

The current user may not have the required permission. Inspect the path and permissions before attempting a fix. Do not use `sudo` automatically.

## 10. Safety Rules

- Verify your current directory before file operations.
- Inspect files before overwriting them.
- Practice in a dedicated directory.
- Avoid destructive commands when unsure.
- Never use elevated permissions without understanding why they are needed.

## 11. Interview Questions

1. What is the Linux root directory?
2. What does `~` represent?
3. What is the difference between an absolute and a relative path?
4. What is the difference between `.` and `..`?
5. What is the difference between `mkdir` and `touch`?
6. What does `ls -la` show?
7. What is the difference between `cp` and `mv`?
8. What is the difference between `>` and `>>`?
9. Why is Linux filename case sensitivity important?
10. How would you troubleshoot a missing-file error?

## 12. Self-Assessment

- [ ] I can navigate between directories.
- [ ] I understand absolute and relative paths.
- [ ] I can create files and directories.
- [ ] I can read, copy, move, and rename files.
- [ ] I understand redirection with `>` and `>>`.
- [ ] I completed the practice assignment.
- [ ] I answered the interview questions.

**Status:** In progress
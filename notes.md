### 1. What is GIT?

- Git is distributed version control system.
- It helps track changed in source code and collaborate with others.

### 2. Installing Git

- download Git
- check version: git --version

### 3. Git Configuration

```bash
git config --global user.name "amannn-s"
git config --global user.email "s.aman230630@gmail.com"
```

### 4. Basic Git Workflow

1. Modify files in your project folder
2. git add <filename> - stage changes
3. git commit -m "message" - commit changes
4. git push - send changed to remote(Github)

### 5. Key Git Commands

#### Initialization

```bash
git init
```

#### Tracking Changes

```bash
git status
```

#### Undoing Changes

```bash
git checkout -- <file>
get reset HEAD <file>
```

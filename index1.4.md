# Assignment 1.4 — Git Essentials I

## Objective
To convert a local project folder into a Git repository and learn basic Git commands such as git init, git status, git add, and git commit.

## 1. Install Git and Verify Installation

Git is a free and open-source version control system used to track changes in files and manage project history.

Git can be downloaded from the official website:

https://git-scm.com/

After installation, I verified Git using the following command:

```bash
git --version
```

This command displays the installed Git version.

## 2. Open the Terminal in the Project Folder

I opened the terminal in Visual Studio Code and navigated to my project folder using the `cd` command.

```powershell
cd web-development-practice
```

## 3. Initialize a Git Repository

I used the following command to initialize a new Git repository:

```bash
git init
```

This command creates a hidden `.git` folder that stores the version history and configuration of the project.

## 4. Configure Git Username and Email

I configured my Git username and email using the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

These details are used to identify the author of each commit.

## 5. Create an HTML File

I created an HTML file named `index.html` inside my project folder.

Example HTML code:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Git Project</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first Git project.</p>
</body>
</html>
```

## 6. Use Basic Git Commands

I practiced the following Git commands:

**A. Check Repository Status**

```bash
git status
```

This command displays the current status of files in the repository.

**B. Add Files to the Staging Area**

```bash
git add .
```

This command adds all new and modified files to the staging area.

**C. Commit Changes**

```bash
git commit -m "Initial commit"
```

This command saves the staged changes in the Git repository.

## 7. Make Three Meaningful Commits

I created three meaningful commits to track different stages of my project.

**Commit 1: Initial Project Setup**

```bash
git add .
git commit -m "Initial project setup"
```

**Commit 2: Add HTML Structure**

After creating the HTML structure, I used:

```bash
git add .
git commit -m "Add HTML structure"
```

**Commit 3: Update Website Content**

After updating the webpage content, I used:

```bash
git add .
git commit -m "Update website content"
```

## 8. Check Commit History

I used the following command to view the commit history:

```bash
git log --oneline
```

This command displays the list of commits with their unique IDs and messages.

## Conclusion

I learned how to install and configure Git, initialize a local Git repository, create HTML files, and track project changes using Git commands. I also learned how to add files to the staging area, create commits, and view the commit history. This assignment helped me understand the basics of version control using Git.
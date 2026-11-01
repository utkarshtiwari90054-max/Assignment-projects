# Assignment 1.5 — GitHub Essentials II

## Objective
To upload a local project to GitHub using Git commands and learn how to connect a local repository with a remote repository.

## 1. Create a GitHub Account

GitHub is an online platform used to store, manage, and share code. It allows developers to collaborate on projects and maintain their project history.

I visited the official GitHub website and created an account.

Website: https://github.com/

## 2. Create a New Public Repository

I logged in to my GitHub account and created a new public repository.

Repository name: `web-development-practice`

Visibility: Public

A public repository allows other people to view the project files and commit history.

## 3. Connect the Local Repository to GitHub

I opened the terminal in my local project folder and connected it to the GitHub repository using the following command:

```bash
git remote add origin https://github.com/YOUR-USERNAME/web-development-practice.git
```

I replaced `YOUR-USERNAME` with my actual GitHub username.

I verified the remote repository using:

```bash
git remote -v
```

## 4. Upload Files Using Git Push

I uploaded my local project files to GitHub using the following commands:

```bash
git branch -M main
git push -u origin main
```

The `git push` command uploads local commits to the remote GitHub repository.

## 5. Add a New File and Push the Second Commit

I created a new file named `about.html` inside my project folder.

Example HTML code:

```html
<!DOCTYPE html>
<html>
<head>
    <title>About My Project</title>
</head>
<body>
    <h1>About My Website</h1>
    <p>This is my second HTML page.</p>
</body>
</html>
```

I added and committed the new file using the following commands:

```bash
git add about.html
git commit -m "Add about page"
```

Then, I uploaded the second commit to GitHub:

```bash
git push
```

## 6. Verify Commit History on GitHub

I opened my public GitHub repository in the browser and checked the uploaded files and commit history.

I verified that both commits were successfully uploaded:

1. Initial project setup.
2. Add about page.

## Conclusion

I learned how to create a GitHub account, create a public repository, connect a local Git repository to GitHub, and upload project files using Git push. I also learned how to add new files, create commits, and verify commit history on GitHub. This assignment helped me understand the basics of using GitHub for online project storage and version control.

## GitHub Repository Link

Paste your public GitHub repository link here:

`https://github.com/YOUR-USERNAME/web-development-practice`
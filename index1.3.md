# Assignment 1.3 — Terminal & Developer Workflow

## Objective
To create and manage a project folder structure using terminal commands and learn basic command-line operations.

## 1. Open the Terminal
I opened the terminal in Visual Studio Code by clicking on Terminal → New Terminal.

## 2. Create the Main Project Folder
I used the following command to create a folder named `web-development-practice`.

```powershell
mkdir web-development-practice
```

## 3. Create Week Folders
I created three folders named `week-1`, `week-2`, and `week-3` inside the main project folder.

```powershell
cd web-development-practice
mkdir week-1, week-2, week-3
```

## 4. Create index.html Files
I created an `index.html` file inside each week folder using the following commands.

```powershell
New-Item week-1/index.html -ItemType File
New-Item week-2/index.html -ItemType File
New-Item week-3/index.html -ItemType File
```

## 5. Practice Terminal Commands

I practiced the following terminal commands:

**A. Navigation (Changing Directories)**

```powershell
cd week-1
cd ..
```

**B. Listing Files and Folders**

```powershell
dir
```

**C. Renaming a Folder**

```powershell
Rename-Item week-1 week-one
Rename-Item week-one week-1
```

**D. Deleting a Folder**

```powershell
mkdir test-folder
Remove-Item test-folder
```

## 6. Open the Project Folder in VS Code

I used the following command to open the project folder in Visual Studio Code.

```powershell
code .
```

## 7. Final Folder Structure

The final folder structure of my project is shown below:

```text
web-development-practice/
│
├── week-1/
│   └── index.html
│
├── week-2/
│   └── index.html
│
└── week-3/
    └── index.html
```

## Conclusion

I learned how to use the terminal to create and manage folders and files. I practiced directory navigation, renaming and deleting folders, and opening a project in Visual Studio Code using command-line instructions. This assignment helped me understand the basic terminal commands used in web development.
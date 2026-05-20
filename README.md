# Internship Project 1 – HTML & CSS Learning Project

Welcome to the **Internship Project 1** repository.  
This project is designed for interns to learn:

- HTML basics
- CSS styling
- Project structure
- Git & GitHub workflow
- Team collaboration using Fork & Pull Request (PR)

---

## Project Structure

```txt
internship-project-1/
│── index.html
│── style.css
│── README.md
│
├── assets/
│   ├── images/
│   ├── icons/
│   └── fonts/
│
└── .gitignore
```

### File Details

| File / Folder | Purpose |
|---|---|
| `index.html` | Main webpage structure |
| `style.css` | Styling and layout |
| `assets/` | Images, icons, fonts |
| `README.md` | Project instructions |
| `.gitignore` | Ignore unnecessary files |

---

# Team Workflow (Fork-Based)

Each intern must **fork the repository**, work in their own branch, and create a **Pull Request (PR)**.

---

## Step 1: Fork the Repository

1. Open the main repository.
2. Click the **Fork** button on GitHub.

This creates your own copy of the repository.

Example:

```txt
Original Repo:
https://github.com/company/internship-project-1

Your Fork:
https://github.com/your-username/internship-project-1
```

---

## Step 2: Clone Your Fork

Open terminal and run:

```bash
git clone https://github.com/your-username/internship-project-1.git
```

Move into project folder:

```bash
cd internship-project-1
```

---

## Step 3: Add Upstream Repository

Add the original repository to receive updates.

```bash
git remote add upstream https://github.com/original-owner/internship-project-1.git
```

Verify remotes:

```bash
git remote -v
```

Expected output:

```txt
origin    https://github.com/your-username/internship-project-1.git
upstream  https://github.com/original-owner/internship-project-1.git
```

---

## Step 4: Create a New Branch

Never work directly on `main`.

Create a feature branch:

```bash
git checkout -b feature-header
```

Examples:

```txt
feature-header
feature-navbar
feature-footer
feature-responsive-ui
```

---

## Step 5: Start Development

Edit:

- `index.html`
- `style.css`

Add images inside:

```txt
assets/images/
```

Example HTML:

```html
<link rel="stylesheet" href="style.css">
```

Example Image:

```html
<img src="assets/images/logo.png" alt="Logo">
```

---

## Step 6: Commit Your Changes

Check modified files:

```bash
git status
```

Add files:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Added responsive navbar"
```

Use meaningful commit messages.

Good examples:

```txt
Added homepage hero section
Fixed navbar alignment
Updated footer styling
Improved responsive layout
```

---

## Step 7: Push Code to Your Fork

Push branch to GitHub:

```bash
git push origin feature-header
```

---

## Step 8: Create Pull Request (PR)

1. Open your fork on GitHub.
2. Click **Compare & Pull Request**.
3. Add title and description.
4. Submit PR to:

```txt
original-repo/main
```

Example title:

```txt
Added responsive header section
```

---

## Step 9: Review & Merge

Project maintainer will:

- Review code
- Suggest improvements
- Approve PR
- Merge into `main`

---

## Step 10: Update Your Fork

Before starting new work:

Switch to main branch:

```bash
git checkout main
```

Get latest changes:

```bash
git pull upstream main
```

Push updated code to your fork:

```bash
git push origin main
```

---

# Rules for Interns

✅ Always create a new branch  
✅ Use meaningful commit messages  
✅ Keep code clean and readable  
✅ Avoid editing another intern’s work without discussion  
✅ Test your UI before pushing code  
❌ Never push directly to `main`

---

# Task Assignment Example

| Intern | Task |
|---|---|
| Intern 1 | Header/Navbar |
| Intern 2 | Hero Section |
| Intern 3 | Footer |
| Intern 4 | Responsive Design |

---

# Learning Goals

By completing this project, interns will learn:

- HTML page structure
- CSS styling
- Responsive design basics
- Git commands
- GitHub workflow
- Branching strategy
- Pull Requests
- Team collaboration

---

## Useful Git Commands

### Check branch

```bash
git branch
```

### Switch branch

```bash
git checkout branch-name
```

### Pull latest changes

```bash
git pull upstream main
```

### Push code

```bash
git push origin branch-name
```

---

Happy Coding 🚀

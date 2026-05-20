# Internship Project 1 – HTML & CSS Learning Project

Welcome to the **Internship Project 1** repository.  
This project is designed for interns to learn:

- HTML basics
- CSS styling
- Project structure
- Git & GitHub workflow
- Team collaboration

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

# Team Workflow (Template-Based)

Each intern must create their **own repository using this template**, complete the assignment, and share the repository link.

---

## Step 1: Create Repository from Template

1. Open the main repository.
2. Click **Use this template** (top right).
3. Select **Create a new repository**.

Choose:

```txt
Repository Name:
internship-project-your-name
```

Example:

```txt
internship-project-john
internship-project-arun
internship-project-megha
```

Click:

```txt
Create repository
```

This creates your own copy of the project.

---

## Step 2: Clone Your Repository

Open terminal and run:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

Move into project folder:

```bash
cd your-repo-name
```

Example:

```bash
cd internship-project-john
```

---

## Step 3: Start Development

Edit:

- `index.html`
- `style.css`

Add assets inside:

```txt
assets/images/
assets/icons/
assets/fonts/
```

Download required assets from **Figma** and place them in the correct folder.

Example HTML:

```html
<link rel="stylesheet" href="style.css">
```

Example Image:

```html
<img src="assets/images/logo.png" alt="Logo">
```

---

## Step 4: Commit Your Changes

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
git commit -m "Completed homepage design"
```

Use meaningful commit messages.

Good examples:

```txt
Added homepage hero section
Implemented navbar design
Completed responsive layout
Updated footer styling
```

---

## Step 5: Push Code to GitHub

Push your work:

```bash
git push origin main
```

---

## Step 6: Share Repository

After completing the assignment:

1. Push all code to GitHub.
2. Share your repository link with the team/mentor.

Example:

```txt
https://github.com/your-username/internship-project-john
```

---

# Rules for Interns

✅ Use the provided template repository  
✅ Keep code clean and readable  
✅ Use proper file names for assets  
✅ Push code regularly  
✅ Test UI before submitting  
❌ Do not delete project structure

---

# Asset Guidelines

### Images

Store inside:

```txt
assets/images/
```

Examples:

```txt
logo.png
banner.jpg
hero-image.webp
```

### Icons

Store inside:

```txt
assets/icons/
```

Preferred format:

```txt
SVG
```

### Fonts

Store inside:

```txt
assets/fonts/
```

Supported formats:

```txt
WOFF2
TTF
OTF
```

---

# Learning Goals

By completing this project, interns will learn:

- HTML structure
- CSS styling
- Responsive UI basics
- Git commands
- GitHub repository management
- Clean project organization
- Working with Figma assets

---

## Useful Git Commands

### Check changes

```bash
git status
```

### Add files

```bash
git add .
```

### Commit changes

```bash
git commit -m "your message"
```

### Push code

```bash
git push origin main
```

---

Happy Coding 🚀

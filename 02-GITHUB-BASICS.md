# 🐙 Getting Started with GitHub

You're already on GitHub! Let's master the basics.

## What is GitHub?

GitHub is:
- A platform to store your code online
- A way to track changes in your projects
- A community to collaborate and learn
- Your portfolio for showing coding skills

## Key Concepts

### Repository (Repo)
A folder that holds all your project files and their history.

### Commit
A snapshot of your code at a specific point in time.

### Branch
A separate version of your code where you can make changes without affecting the main code.

### Pull Request (PR)
A way to suggest changes and have them reviewed before adding to main code.

---

## Essential GitHub Tasks

### 1. Clone a Repository (Download)

```bash
git clone https://github.com/username/repository-name.git
cd repository-name
```

### 2. Create a New Repository

1. Go to https://github.com/new
2. Name your repo
3. Add description (optional)
4. Choose "Public" or "Private"
5. Click "Create repository"

### 3. Make Your First Commit

```bash
# In your repo folder
git add .
git commit -m "Initial commit"
git push origin main
```

### 4. Create a Branch

```bash
git checkout -b my-feature
# Make changes...
git add .
git commit -m "Add new feature"
git push origin my-feature
```

Then open a Pull Request on GitHub!

---

## Common Git Commands

| Command | What it does |
|---------|-------------|
| `git status` | See what's changed |
| `git add .` | Prepare changes to save |
| `git commit -m "message"` | Save changes with a description |
| `git push` | Upload to GitHub |
| `git pull` | Download latest changes |
| `git log` | See history of changes |

---

## GitHub Tips for Beginners

✅ **DO:**
- Write clear commit messages ("Add login button" not "update")
- Commit frequently (save progress often)
- Read README files in repos you explore
- Star repos you like (bookmark them)
- Follow developers whose work you admire

❌ **DON'T:**
- Commit sensitive info (passwords, API keys)
- Force push to main branch
- Leave repos without documentation
- Ignore error messages

---

## Next Steps

→ Move to: **[Python Beginner's Guide](./03-PYTHON-BEGINNERS-GUIDE.md)**

# 💻 Installation Guide - All Operating Systems

## For Windows Users

### Step 1: Install Git
1. Go to https://git-scm.com/download/win
2. Click "Download for Windows"
3. Run the installer
4. Keep clicking "Next" (default settings are fine)
5. Finish installation

**Verify**: Open Command Prompt and type `git --version`

### Step 2: Install Visual Studio Code
1. Go to https://code.visualstudio.com/
2. Click the Windows download button
3. Run the installer
4. Check "Add to PATH" during installation
5. Complete installation

### Step 3: Install Python
1. Go to https://www.python.org/downloads/
2. Download Python 3.11 or latest
3. **IMPORTANT**: Check "Add Python to PATH" during installation
4. Click Install Now

**Verify**: Open Command Prompt and type `python --version`

---

## For Mac Users

### Step 1: Install Homebrew (Package Manager)
1. Open Terminal
2. Copy & paste this:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
3. Follow prompts

### Step 2: Install Git
```bash
brew install git
```

**Verify**: Type `git --version`

### Step 3: Install VS Code
1. Go to https://code.visualstudio.com/
2. Download for Mac
3. Drag to Applications folder

### Step 4: Install Python
```bash
brew install python3
```

**Verify**: Type `python3 --version`

---

## For Linux Users (Ubuntu/Debian)

### Step 1: Update Package Manager
```bash
sudo apt update
```

### Step 2: Install Git
```bash
sudo apt install git
```

### Step 3: Install VS Code
```bash
sudo apt install code
```

### Step 4: Install Python
```bash
sudo apt install python3
```

**Verify all**: Type `git --version`, `python3 --version`

---

## ✅ Post-Installation Setup

### Configure Git (One-time)
Open Terminal/Command Prompt:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Install VS Code Extensions
1. Open VS Code
2. Go to Extensions (left sidebar, icon with 4 squares)
3. Search and install:
   - **Python** (by Microsoft)
   - **Pylance** (for Python support)
   - **GitHub Copilot** (optional but helpful)
   - **GitLens** (for Git integration)

---

## 🎉 You're Ready!

Once all tools are installed and verified, move to: **[Getting Started with GitHub](./02-GITHUB-BASICS.md)**

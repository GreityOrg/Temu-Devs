# 🚀 Contributing to the Website Project

Welcome, and thank you for your interest in contributing!  
This project is built by a team of passionate developers, and we’re excited to have you join us.

Whether you’re new to coding or experienced, this guide will walk you through how we work together.

---


## 📌 Project Workflow Overview

- No one pushes directly to `main`
- All new work happens in **feature branches off `dev`**
- Every change must go through a **Pull Request (PR)** for review
- Once reviewed and approved, your work is merged into `dev`
- `dev` will occasionally be merged into `main` for releases

- **This keeps our code safe and avoids mistakes.**

---

## Before we get started make sure you have VS code installed and git installed on your device

## 🛠️ How to Set Up Git on Your Device

If this is your first time using Git on your computer, follow these steps:

### 1️⃣ Install Git

- Download and install Git from:  
  [https://git-scm.com/downloads](https://git-scm.com/downloads)
- Follow the installer instructions.  
  You can leave most options as default.

---

### 2️⃣ Check That Git is Installed

After installation, open your terminal (Command Prompt, PowerShell, or VS Code Terminal) and run:
```bash
git --version
```
If you see a version number, Git is installed correctly.

---

### 3️⃣ Set Up Your Git Username and Email

These details will be attached to your commits.

In your terminal, run:
```bash
git config --global user.name "Your Full Name"
git config --global user.email "youremail@example.com"
```
Example:
```bash
git config --global user.name "Greity Mandela"
git config --global user.email "Greitya@example.com"
```
To confirm your settings:
```bash
git config --global --list
```

---

# 🚀 Now that you have Git installed, lets set you up with the project

## 📦 How to Get Started

### 1️⃣ Clone the Repository

If you haven’t cloned the project yet:
```bash
git clone https://github.com/GreityOrg/Temu-Devs.git
cd Temu-Devs
```
### 2️⃣ Fetch All Branches
To make sure you have the latest:
```bash
git fetch --all
```
### 3️⃣ Switch to the `dev` Branch
```bash
git checkout dev
git pull
```

### 4️⃣ Create Your Own Feature Branch
Use this naming format:
```
your-name/short-feature-description
```
Example:
```bash
git checkout -b patrick/home-page
```

### 5️⃣ Make Your Changes

- Use clean, readable code.
- Test your changes in your browser.
- Avoid changing too many things at once — focus on one issue/feature at a time.
- Don’t touch files you aren’t working on.

---

## 💾 Commit and Push Your Work

### 6️⃣ Stage and Commit Your Changes
```bash
git add .
git commit -m "Clear, short message describing what you did"
```
**Commit messages should explain the change.**
Example:
```bash
git commit -m "Add footer with social icons and copyright"
```

### 7️⃣ Push Your Feature Branch
```bash
git push origin your-name/feature-description
```

---

## 📤 Open a Pull Request (PR)

- Go to our GitHub repo
- Click **Pull Requests**
- Click **New Pull Request**
- Set the **base branch** to `dev`
- Set the **compare branch** to your feature branch
- Add a clear title and description of what you changed
- Request a review by tagging **@Sebata**

---

## 📏 Branch Naming Rules

Use this format for your branch names:
```
your-name/feature-description
```
Examples:
- `thato/add-navbar`
- `jane/update-about-page`

This keeps our repo organized and easy to manage.

---

## 🎨 Code Style Guidelines

- Use consistent indentation (2 or 4 spaces — follow existing code)
- No inline CSS (unless necessary)
- Keep HTML, CSS, and JS in separate files when possible
- Test your changes in a browser before committing
- Keep your changes focused — one branch, one feature

---

## 📝 How to Pick a Task

- Check the **Issues** tab in the repo.
- Choose an open issue you’d like to work on.
- Comment on it to claim it:
  > *“I’ll work on this”*
- Or ask @Sebata if you’re unsure where to start.

---

## ❓ Need Help?

If you get stuck:
- Check if someone else has asked the same question in **Issues**
- Ask in our team group chat
- Or ping **@Sebata** directly on GitHub

---

## 💡 Pro Tips for New Contributors

- Pull the latest changes from `dev` before starting new work.
- Don’t work on `main` — it’s protected for a reason.
- Always create a new branch for each task.
- Commit often with clear, descriptive messages.
- Read other people's Pull Requests to learn and see good practices.

---

## ✨ Final Note

You don’t have to be an expert to contribute.  
This is a learning-first, collaborative project — so ask questions, make mistakes, and help others too.

**Let’s build something awesome together 🚀**

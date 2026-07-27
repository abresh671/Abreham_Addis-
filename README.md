## Abreham Addis review

## 📋 Table of Contents

- [Week 1 Review: Web & Frontend Fundamentals](#week-1-review-web--frontend-fundamentals)
  - [Why Software & How It Works](#why-software--how-it-works)
  - [Website Basics: Frontend vs Backend](#website-basics-frontend-vs-backend)
  - [How the Web Communicates](#how-the-web-communicates)
    - [The Client-Server Model](#the-client-server-model)
    - [HTTP Basics (Requests & Responses)](#http-basics-requests--responses)
    - [What Is an API?](#what-is-an-api)
- [Development Environment Setup & Git Workflow Guide](#development-environment-setup--git-workflow-guide)
  - [🎯 Overview](#-overview)
  - [🛠️ Environment Setup](#%EF%B8%8F-environment-setup)
    - [Visual Studio Code (VS Code)](#visual-studio-code-vs-code)
    - [Node.js Environment](#nodejs-environment)
  - [🔌 VS Code Extensions](#-vs-code-extensions)
    - [1. Prettier - Code Formatter](#1-prettier---code-formatter)
    - [2. Live Server](#2-live-server)
  - [🔄 Git & GitHub Workflow](#-git--github-workflow)
    - [1. Cloning a Repository](#1-cloning-a-repository)
    - [2. Making & Verification of Changes](#2-making--verification-of-changes)
    - [3. Staging and Committing Changes](#3-staging-and-committing-changes)
    - [4. Pushing Changes to Remote](#4-pushing-changes-to-remote)
  - [📌 Quick Command Reference](#-quick-command-reference)
  - [📝 Summary](#-summary)
  - [Week 1 Reflection](#week-1-reflection)
  - [Gratitude](## Gratitude)

# Week 1 Review: Web & Frontend Fundamentals

## Why Software & How It Works
At its core, software is built to solve real-world problems by automating tasks and making processes faster. Instead of doing everything manually, we write programs that take input, process logic, and output a result. 

## Website Basics: Frontend vs Backend
Every web application is split into two main sides:

* **Frontend (Client-side):** This is everything the user sees and interacts with directly on their screen—buttons, forms, layouts, and animations. A frontend developer turns design ideas into a functional interface using HTML, CSS, and JavaScript.
* **Backend (Server-side):** This is the hidden engine behind the curtain. It handles database storage, user authentication, business logic, and security.

## How the Web Communicates

### The Client-Server Model
Web applications rely on a simple client-server setup:
* **Client:** The device or browser (like Chrome or Firefox) requesting data or pages.
* **Server:** A remote machine storing the website's files, databases, and application logic.

### HTTP Basics (Requests & Responses)
Clients and servers communicate using HTTP/HTTPS rules:
* **Request:** The browser asks the server for specific information (for example, fetching a page or sending a login form).
* **Response:** The server processes that request and sends back a status code (like `200 OK` or `404 Not Found`) along with the requested web content.

### What Is an API?
An **API (Application Programming Interface)** acts as a bridge that allows different software applications to talk to each other. In web development, frontend applications use APIs to send data to or fetch data from the backend without needing direct access to the database.

---
# Development Environment Setup & Git Workflow Guide

Welcome to the documentation for today's lesson on setting up a modern web development environment and mastering fundamental Git/GitHub terminal workflows. This repository serves as a structured guide and assignment submission reflecting all the key concepts covered.

---

## 🎯 Overview

Setting up a efficient local development workspace is essential for modern software engineering. This guide demonstrates how to install key runtime tools, configure an integrated development environment (IDE), enhance developer productivity with extensions, and maintain version control using Git and terminal commands.

---

## 🛠️ Environment Setup

### Visual Studio Code (VS Code)
- **What it is:** A lightweight, highly extensible code editor by Microsoft.
- **Installation:** Downloaded and installed from the official website ([code.visualstudio.com](https://code.visualstudio.com/)).
- **Verification:** Opened VS Code and initialized working directories.

### Node.js Environment
- **What it is:** A JavaScript runtime built on Chrome's V8 engine that enables running JavaScript outside the browser.
- **Installation:** Downloaded the recommended LTS (Long Term Support) version from [nodejs.org](https://nodejs.org/).
- **Verification:**
  Open your terminal and verify installation by checking the versions:
  ```bash
  node -v
  npm -v
  ```

---

## 🔌 VS Code Extensions

Extensions enhance the functionality of VS Code to boost productivity and code quality.

### 1. Prettier - Code Formatter
* **Purpose:** Automatically formats your code (JavaScript, HTML, CSS, JSON, etc.) to enforce consistent code styling.
* **Setup & Usage:**
  1. Installed **Prettier** via the Extensions tab (`Ctrl+Shift+X` or `Cmd+Shift+X`).
  2. Configured VS Code settings to enable **Format on Save**:
     - Go to Settings (`Ctrl+,` / `Cmd+,`) -> Search for `Format On Save` -> Check the box.

### 2. Live Server
* **Purpose:** Launches a local development server with a live reload feature for static and dynamic web pages.
* **Setup & Usage:**
  1. Installed **Live Server** by Dayeed Ritwick from the Extensions marketplace.
  2. Clicked the **"Go Live"** button on the bottom status bar (or right-click `index.html` -> *Open with Live Server*).
  3. Automatically previews live changes in the web browser upon saving files.

---

## 🔄 Git & GitHub Workflow

A complete terminal walkthrough on connecting local code workspaces with remote GitHub repositories.

### 1. Cloning a Repository
To bring a remote repository into your local machine:
```bash
# Clone the repository using HTTPS or SSH URL
git clone <repository-url>

# Navigate into the project folder
cd <repository-folder-name>

# Open the project directory directly in VS Code
code .
```

### 2. Making & Verification of Changes
Edit files or create new project assets inside VS Code. To monitor workspace status:
```bash
# Check modified files and uncommitted changes
git status
```

### 3. Staging and Committing Changes
Group your work into logical commits with meaningful messages:
```bash
# Stage specific files or all modified files
git add .

# Create a commit with a clear description
git commit -m "Feat: Completed environment setup and initial project files"
```

### 4. Pushing Changes to Remote
Upload your local commits back to the GitHub remote repository:
```bash
# Push commits to the default main/master branch
git push origin main
```

---

## 📌 Quick Command Reference

| Command | Description |
| :--- | :--- |
| `git clone <url>` | Clones remote repository to local machine |
| `git status` | Displays working tree status |
| `git add .` | Stages all changes for the next commit |
| `git commit -m "msg"` | Saves staged snapshot with a descriptive message |
| `git push origin main` | Uploads local branch commits to GitHub |

---

## 📝 Summary

Through this exercise, we successfully:
1. Established a clean local development workspace with **VS Code** and **Node.js**.
2. Automated code styling using **Prettier** and streamlined live previews with **Live Server**.
3. Practiced end-to-end version control using **Git terminal commands** to clone, edit, commit, and push updates to GitHub.
README.md
Displaying README.md.

## Week 1 Reflection
Week 1 gave me a solid overview of what actually happens behind the scenes when we browse the web. Learning how clients, servers, HTTP requests, and APIs fit together makes frontend development feel much more grounded, giving context to how code written locally eventually reaches an end user's screen. none gonna lie i am quite liking this course more and more by a day.
## Gratitude 
Thanks for our mentor and the people who made this course really happen I am really greatfull.
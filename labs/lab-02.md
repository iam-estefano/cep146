# Lab 2
# Software Development Environment Lab Exercises

## Exercise 1: Development Environment Setup Planning

- **Student:** Paul Estefano Coronado Cáceres
- **Professor:** Raymond Wong
- **Course:** CEP 146 - Essential Tooling for Programmers
- **Scenario:** Building a simple webstie

---

## 1. Scenario Analysis

This scenario involves building a simple business website with text, images, and contact forms. This requires a lightweight but capable development environment focused on front-end technologies like HTML, CSS, and JavaScript, with tools for version control, live preview, and form handling.

---

## 2. Environment Planning

### IDE Selection
**Chosen IDE:** Visual Studio Code (VS Code)

Visual Studio Code is the most suitable IDE for this project because:
- It has native support for HTML, CSS, and JavaScript with syntax highlighting and autocompletion
- It is free, lightweight, and cross-platform (Windows/Mac/Linux)
- It has a large extension ecosystem specifically tailored for web development
- It integrates directly with Git for version control

**Important Extensions:**
- **Live Server**: launches a local development server with live reload on save
- **Prettier**: automatic code formatting for clean, consistent code
- **HTML CSS Support**: enhanced IntelliSense for CSS classes in HTML files

---

### Additional Tools

| Tool | Purpose | Justification |
|------|---------|---------------|
| Git | Version control | Track changes, manage project history, and collaborate |
| GitHub | Remote repository | Cloud backup and collaboration platform |
| Google Chrome + DevTools | Browser testing | Browser with built-in inspector for debugging layout and styles |
| Formspree / EmailJS | Contact form handling | Free services to handle form submissions without a backend server |
| Figma (optional) | UI planning | Quickly sketch page layout before coding |

---

### Hardware Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| CPU | Dual-core 1.6GHz | Quad-core 2.0GHz |
| RAM | 4GB | 8GB or more |
| Storage | 10GB free | 20GB SSD or more |
| Display | 1280x768 | 1920x1080 |
| Internet | Required | Broadband |

-> For this project, any modern computer meets these requirements comfortably. My current setup (i7-14700K, 32GB DDR5, 1TB NVMe) exceeds all requirements.

---

### Team Collaboration Strategy

Even though this lab is individually, the following collaboration tools would be used in a team setting:

- **GitHub** — shared repository where both members push and pull changes via branches
- **GitHub Issues** — task tracking and assignment
- **VS Code Live Share** — real time collaborative coding sessions
- **Discord** — communication and file sharing platform

In a team of 2 members, the recommended split would be:
- **Member 1:** HTML structure and content
- **Member 2:** CSS styling and contact form integration with JavaScript.

---

### Estimated Setup Time and Complexity

| Task | Estimated Time | Complexity |
|------|---------------|------------|
| Install VS Code | 5 minutes | Low |
| Install Git | 5 minutes | Low |
| Configure Git account (name, email) | 5 minutes | Low |
| Install VS Code extensions | 10 minutes (depends on internet connection) | Low |
| Create GitHub repo and clone locally | 10 minutes | Medium |
| Set up project folder structure | 5 minutes | Low |
| **Total** | **40 minutes aprox** | **Low** |

---

## 3. Setup Guide — Step-by-Step Installation Checklist

### Step 1 — Install Visual Studio Code
- [ ] Go to https://code.visualstudio.com
- [ ] Download the installer for your Operating System (Windows/Mac/Linux)
- [ ] Run the installer and follow the prompts
- [ ] Launch VS Code to verify installation

### Step 2 — Install Git
- [ ] Go to https://git-scm.com
- [ ] Download the installer for your OS
- [ ] Run the installer (use default settings)
- [ ] Open terminal and run `git --version` to verify

### Step 3 — Configure Git
- [ ] Run `git config --global user.name "Your Name"`
- [ ] Run `git config --global user.email "your@email.com"`

### Step 4 — Install VS Code Extensions
- [ ] Open VS Code and go to Extensions (Ctrl+Shift+X)
- [ ] Search and install: **Live Server**
- [ ] Search and install: **Prettier - Code Formatter**
- [ ] Search and install: **HTML CSS Support**

### Step 5 — Create GitHub Repository
- [ ] Go to https://github.com and sign in
- [ ] Click **New Repository**
- [ ] Name it (e.g., `simple-business-website`)
- [ ] Set visibility to Public
- [ ] Click **Create Repository**

### Step 6 — Clone Repository Locally
- [ ] Copy the repository URL from GitHub
- [ ] Open terminal and run `git clone <repository-url>`
- [ ] Open the cloned folder in VS Code: `code <folder-name>`

### Step 7 — Set Up Project Folder Structure
- [ ] Create the following files and folders:
      <img width="287" height="211" alt="image" src="https://github.com/user-attachments/assets/9c3ca614-53ac-46e8-80ae-4e5d241937ba" />


### Step 8 — Set Up Contact Form
- [ ] Go to https://formspree.io and then create a free account
- [ ] Create a new form and copy the endpoint URL
- [ ] Add the form endpoint to your `contact.html`

### Step 9 — Test the Environment
- [ ] Open `index.html` in VS Code
- [ ] Right-click and **Open with Live Server**
- [ ] Verify the page loads in the browser
- [ ] Make a small change and confirm live reload works

### Step 10 — Push First Commit
- [ ] In terminal: `git add .`
- [ ] `git commit -m "Initial project setup"`
- [ ] `git push origin main`
- [ ] Verify the files that appear on GitHub

---

## Summary

This development environment plan covers all required areas for building a simple business website. Visual Studio Code was selected as the primary IDE due to its robust web development support, free availability, and seamless Git integration. The total setup time is approximately 40 minutes, making it accessible for developers of any experience level. All tool choices are justified based on the specific needs of a front end web project with a contact form.

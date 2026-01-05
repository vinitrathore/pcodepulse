# 🚀 CodePulse – AI Code Reviewer (VS Code Extension)

CodePulse is an AI-powered Visual Studio Code extension that helps developers improve their code quality.  
It reviews your code and provides cleaner, optimized, and more readable versions that you can insert directly into your editor.

This tool is useful for beginners as well as experienced developers who want better code structure, readability, and best practices.

🌐 **Official Website**  
https://codpulse.netlify.app

---

## ✨ Features

- 🔍 Review selected code or the entire file  
- 🤖 AI-based intelligent code review  
- 🧠 Supports multiple programming languages  
- ✂️ Replace selected code or the full file  
- 🪄 One-click insertion of improved code  
- 📂 Automatically reopens file if it is closed  
- ⌨️ Keyboard shortcut support  

---

## 📦 Extension Details

- **Extension Name:** CodePulse  
- **Publisher:** Vinit Rathore  
- **Version:** 0.0.1  
- **Category:** Other  
- **Minimum VS Code Version:** ^1.105.0  

---

## 🚀 Installation Guide

### Install Using `.vsix` File

Currently, CodePulse is installed using a `.vsix` file.

### Step 1: Download the Extension
1. Go to the GitHub repository of CodePulse  
2. Open the **Releases** section  
3. Download the `.vsix` file  
4. Save it on your computer  

### Step 2: Install in Visual Studio Code
1. Open **Visual Studio Code**
2. Press `Ctrl + Shift + X` to open Extensions
3. Click the **three-dot menu** (top-right)
4. Select **Install from VSIX…**
5. Choose the downloaded `.vsix` file
6. Reload VS Code when asked

---

## 🔧 Configuration (Required)

After installation, you must configure CodePulse once.

### Step 1: Get Your API Key
1. Visit 👉 https://codpulse.netlify.app
2. Sign up or log in
3. Open your **Dashboard**
4. Generate your **User API Key**

### Step 2: Add Settings in VS Code
1. Open **VS Code**
2. Go to **File → Preferences → Settings**
3. Search for **CodePulse**
4. Add the following values:

```json
{
  "codepulse.userKey": "PASTE_YOUR_USER_API_KEY_HERE",
  "codepulse.serverUrl": "https://codepulse-backend-gv81.onrender.com"
}

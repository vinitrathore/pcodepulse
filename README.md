# 🚀 CodePulse – AI Code Reviewer (VS Code Extension)

CodePulse is a powerful Visual Studio Code extension that reviews your code using AI and suggests cleaner, better, and optimized versions.  
You can review selected code or the entire file and insert the improved code with a single click.

🌐 **Official Website**  
https://codpulse.netlify.app

---

## ✨ Features

- 🔍 Review selected code or full file
- 🤖 AI-powered intelligent code review
- 🧠 Language-aware suggestions
- ✂️ Replace selected code or entire file
- 📂 Automatically reopens file if closed
- 🪄 One-click improved code insertion
- ⌨️ Keyboard shortcut support

---

## 📦 Extension Details

- **Name:** CodePulse  
- **Publisher:** Vinit Rathore  
- **Version:** 0.0.1  
- **Category:** Other  
- **VS Code Required:** ^1.105.0  

---

## 🚀 Getting Started (Step-by-Step)

### Step 1: Download the Extension (Later)
- Open **VS Code**
- Go to **Extensions Marketplace** (Later)
- Search for **CodePulse** (Later)
- Click **Install** (Later)
- Download the extension from Github (for now download .vsix) 
---
## How to Install in VS Code

Follow these steps to install the extension in Visual Studio Code using the `.vsix` file.

### 1. Download the Extension
- Visit the [GitHub repository](#) of the extension.
- Locate the `.vsix` file (usually under the **Releases** section).
- Download the file to a folder on your computer.

### 2. Open Visual Studio Code
- Launch VS Code on your machine.

### 3. Open the Extensions Menu
- Click on the **Extensions** icon on the left sidebar (four squares).  
- Alternatively, press:
  - `Ctrl + Shift + X` on Windows/Linux  
  - `Cmd + Shift + X` on macOS

### 4. Install from VSIX
- Click the **three-dot menu** at the top-right corner of the Extensions pane.
- Select **“Install from VSIX…”**
- Navigate to the folder where the `.vsix` file was downloaded.
- Select the file and click **Open**.

### 5. Reload VS Code
- After installation, VS Code may prompt you to **Reload**.
- Click **Reload** to activate the extension.

### ✅ Notes
- Make sure VS Code is updated to the latest version for compatibility.
- This method works for extensions not published in the VS Code Marketplace.


### Step 2: Visit the Website & Login
- Open 👉 https://codpulse.netlify.app
- Sign up or log in
- Go to your **Dashboard**
- Generate your **User API Key**

---

### Step 3: Configure CodePulse in VS Code

Open VS Code Settings:

File → Preferences → Settings → CodePulse


Add the following values:

```json
{
  "codepulse.userKey": "YOUR_GENERATED_USER_KEY",
  "codepulse.serverUrl": "https://codepulse-backend-gv81.onrender.com"
}

✅ Now CodePulse is ready to use.

⌨️ How to Use CodePulse
Method 1: Keyboard Shortcut
Ctrl + Alt + R

Method 2: Right Click


Open any file in VS Code


Select code (optional)


Right-click → AI Code Review (CodePulse)



🧠 How CodePulse Works


Open a code file


Select code (or leave empty to review full file)


Run CodePulse


Code is securely sent to the AI backend


Review opens in a side panel


Improved code is shown separately


Click Insert Improved Code


If the file is closed:


CodePulse asks for permission


Reopens the file


Inserts the improved code automatically



🖥️ Review Panel


Shows AI review feedback


Displays improved code clearly


Button to insert improved code instantly



📁 Project Structure
codepulse/
│
├── extension.js
├── package.json
├── images/
│   └── vlogosvg.png
└── README.md


🛠️ Tech Stack


VS Code Extension API


Node.js


node-fetch


Google Gemini AI (via backend)



❗ Common Issues & Fixes
❌ “Open a file first”
✔️ Open any file in the editor
❌ “Set userKey and serverUrl in settings”
✔️ Add both values correctly in VS Code settings
❌ File closed while inserting code
✔️ Click Yes when prompted to reopen the file

🌍 Live Frontend
Manage your account, API keys, and plans here:
👉 https://codpulse.netlify.app

👨‍💻 Author
Vinit Rathore

⭐ Support & Feedback
If you like CodePulse:


⭐ Star the repository


🐞 Report bugs


💡 Suggest new features



🚧 Coming Soon


VS Code Marketplace optimization


Screenshots & demo videos


CHANGELOG.md


Privacy Policy & Terms


Subscription plans



Happy Coding with CodePulse 🚀

---

If you want next, I can:
- Make it **perfect for VS Code Marketplace**
- Write **Privacy Policy / Terms**
- Add **pricing & product copy**
- Create **landing page content**

Just say 👍

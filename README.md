# codepulse

**AI Code Reviewer for VS Code**

`codepulse` is a VS Code extension that uses AI (Gemini API) to review your code and suggest improvements for readability, efficiency, and best practices. It works with multiple languages like JavaScript, Python, C++, Java, C, React, and more.

---

## Features

- Review your code using a single command or keyboard shortcut (`Ctrl+Alt+R`).
- Highlights inefficient code and suggests improvements.
- Works on selected code or entire files.
- Supports multiple programming languages.
- Shows a panel with **AI review** and **improved code**.
- Copy or replace code directly in your editor.

---

## Requirements

- VS Code v1.105.0 or later
- Node.js installed
- Gemini API Key (set in VS Code settings)

---

## Installation (from VSIX)

1. Download the `.vsix` file (e.g., `codepulse-0.0.1.vsix`).
2. Open VS Code.
3. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS) to open the Command Palette.
4. Type `Extensions: Install from VSIX` and select it.
5. Browse to your `.vsix` file and click **Open**.
6. The extension will be installed.

---

## Extension Settings

After installing, you need to set your **Gemini API Key**:

1. Go to **File → Preferences → Settings** (or `Ctrl+,`).
2. Search for `codepulse.geminiApiKey`.
3. Enter your Gemini API Key.

---

## How to Use codepulse AI Code Reviewer

1. Open any code file in VS Code.
2. Select the portion of code you want to review.  
   - If no code is selected, the extension will review the entire file.
3. Run the AI Code Review command:
   - **Command Palette:** Press `Ctrl+Shift+P` → type `AI Code Review (codePulse)` → hit Enter
   - **Keyboard Shortcut:** Press `Ctrl+Alt+R` (works when editor is focused)
   - **Right-Click Menu:** Right-click inside the editor → choose `AI Code Review (codePulse)`
4. A panel will appear showing:
   - **AI Review:** Explanation of issues and suggestions.
   - **Improved Code:** Optimized version of your code.
5. Click **Insert Improved Code** to replace the selected code (or the whole file if nothing is selected).

> ⚠️ Tip: Hover over the **Insert Improved Code** button to see a tooltip warning:  
> "Before clicking, select the area where you want to paste. Otherwise, it will append to your active file."

---

## Known Issues

- Requires a valid Gemini API key.
- Internet connection is needed to communicate with the AI API.
- Only works with VS Code versions >= 1.105.0.

---

## Release Notes

### 0.0.1
- Initial release of codepulse.

---

## For More Information

- [VS Code Extensions Documentation](https://code.visualstudio.com/api)
- [Gemini AI API](https://developers.google.com/)

---

**Enjoy reviewing your code with AI!**

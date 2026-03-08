# Eye-Friendly Paper Themes

By **Changhee Ryu** | [GitHub Repository](https://github.com/Changhee-Ryu/vscode-theme)
A collection of comfortable, paper-inspired VS Code color themes designed by an expert visual designer to reduce eye strain, maximize readability, and provide rich color syntax highlighting for modern languages (Python, JS/TS, JSON, .env, XML/HTML, etc).

## 🌿 The 3 Themes

This package includes three variants to suit your environment and lighting:

1. **Eye-Friendly Paper Light**: A soft ivory/off-white paper background. The best choice for brightly lit rooms. Reduces glare compared to stark white themes.
2. **Eye-Friendly Paper Dark Green**: A muted forest-green background. Offers organic, deep natural tones. Excellent for reducing eye fatigue during long night coding sessions.
3. **Eye-Friendly Paper Dark Sepia**: A warm, dark sepia background. Drastically reduces blue light while maintaining high contrast.

## 🚀 Installation & Usage

There are two main ways to use this theme: 

### Method 1: Direct Usage (Development Mode)
1. Open this extension folder in VS Code.
2. Press **F5** to start the Extension Development Host.
3. In the new VS Code window that opens, press `Cmd+Shift+P` (Mac) or `Ctrl+Shift+P` (Windows).
4. Type **Preferences: Color Theme** and press Enter.
5. Select one of the `Eye-Friendly Paper` themes from the list.

### Method 2: Package & Install (VSIX)
To permanently install this theme in your main VS Code environment without running the debugger:
1. Open your terminal in this directory.
2. Install the VS Code Extension manager globally (if you haven't already):
   ```bash
   npm install -g @vscode/vsce
   ```
3. Package the extension:
   ```bash
   vsce package
   ```
   This will create a `.vsix` file (e.g., `eye-friendly-paper-theme-1.0.0.vsix`) in the folder.
4. Install the packaged extension in VS Code:
   * Go to the **Extensions** view (`Cmd+Shift+X`).
   * Click the `...` (Views and More Actions) menu at the top right of the Extensions panel.
   * Select **Install from VSIX...**
   * Choose the `.vsix` file you just created.
5. Go to **Preferences: Color Theme** and select your desired `Eye-Friendly Paper` theme!

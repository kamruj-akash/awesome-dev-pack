# Awesome Dev Pack

**JavaScript Developer's Extension Collection for VS Code**

An efficient and developer-friendly extension pack curated for JavaScript and modern web development, designed for seamless workflow in Visual Studio Code.

---

## About the Author

**KAMRUZZAMAN Akash** – A passionate Full-Stack Developer based in Dhaka, Bangladesh. I love building clean, scalable, and intuitive applications that offer real value.

– **Website**: [kamruj.vercel.app](https://kamruj.vercel.app)  
– **GitHub**: [@kamruj-akash](https://github.com/kamruj-akash)  
– **LinkedIn**: [kamruj-akash](https://www.linkedin.com/in/kamruj-akash/)  
– **Email**: source.akash@gmail.com

---

## What’s Inside

This extension pack bundles essential tools to supercharge your JavaScript development environment:

- Auto-close & rename HTML tags
- Spell checking
- Live previews & error highlighting
- ESLint & Prettier for code consistency
- Tailwind CSS support
- React/JS snippets
- REST API testing tools
- Enhanced terminal logging
- And many more...

(For full list, see the package manifest.)

---

## Why Use It?

- **Ready-to-use**: Installs all vital dev-extensions in one click
- **Clean & Focused**: Tailored specifically for JavaScript and frontend workflows
- **Save Time**: No need to search and install multiple extensions manually

---

## Quick Install

Install via VS Code Marketplace:

```sh
ext install kamruj-akash.awesome-dev-pack

## You can also change setting.json file

- Split the editor (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on Windows and Linux).
- Toggle preview (write 'setting.json) an hit enter.
- remove all codes and paste code from below.

```

{
"workbench.colorTheme": "Omni",

// 🎨 Custom UI & Terminal Color (Merged Block)
"workbench.colorCustomizations": {
"[Learn with Sumit - Professional]": {
"toolbar.activeBackground": "#80CBC426",
"activityBarBadge.background": "#80CBC4",
"activityBar.activeBorder": "#80CBC4"
// ... (other UI colors)
},
// Terminal Theme Customization
"terminal.background": "#131a19",
"terminal.foreground": "#9ba9e3"
// ... (other terminal colors)
},

// ⚙️ General Editor & Explorer Settings
"workbench.editor.empty.hint": "hidden",
"liveServer.settings.CustomBrowser": "chrome",
"explorer.confirmDelete": false,
"explorer.confirmDragAndDrop": false,
"files.autoSave": "afterDelay",
"editor.renderWhitespace": "none",
"editor.guides.indentation": false,

// 🔐 Security Settings
"security.workspace.trust.untrustedFiles": "open",

// 🖋️ Editor Appearance
"editor.fontSize": 18,
"editor.fontFamily": "Fira Code, Operator Mono",
"editor.fontLigatures": true,
"editor.wordWrap": "on",
"editor.minimap.enabled": false,
"editor.tokenColorCustomizations": {
"textMateRules": [
{
"scope": "comment",
"settings": {
"fontStyle": "italic"
}
}
]
},

// 🖱️ Cursor Customization
"editor.cursorSmoothCaretAnimation": "on",
"editor.cursorBlinking": "expand",

// ===================================================================
// 🧑‍💻 Code Formatting & Linting (ESLint + Prettier)
// ===================================================================
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true,

// ESLint-
"eslint.validate": [
"javascript",
"javascriptreact",
"typescript",
"typescriptreact"
],

"editor.codeActionsOnSave": {
"source.fixAll.eslint": "explicit",
"source.organizeImports": "explicit"
},
"eslint.alwaysShowStatus": true,
// ===================================================================

// 🔲 Terminal Font Size & Line Height
"terminal.integrated.fontSize": 16,
"terminal.integrated.lineHeight": 1.3,

// 🧭 Sidebar Config
"workbench.secondarySideBar.defaultVisibility": "hidden",
"[snippets]": {
"editor.defaultFormatter": "vscode.json-language-features"
},
"workbench.startupEditor": "none",
"git.openRepositoryInParentFolders": "never",
"terminal.integrated.env.osx": {},
"console-ninja.featureSet": "Community",
"workbench.iconTheme": "mizu",
"workbench.externalBrowser": "chrome"
}

```

**Enjoy!**
```

# Textab

<div align="center">
	<img 
		src="./src/vs/workbench/browser/parts/editor/media/slice_of_void.png" 
		alt="Textab Welcome" 
		width="300" 
		height="300" 
	/>
</div>

**Textab is a Cursor alternative.**

Use AI agents on your codebase, checkpoint and visualize changes, and bring any model or host locally. Textab sends messages directly to providers without retaining your data.

## What is Textab?

Textab is a powerful code editor built on top of VS Code that integrates AI capabilities directly into your development workflow. Unlike other AI-powered editors, Textab:

- **Preserves your privacy** - Messages go directly to AI providers without being stored
- **Works with any model** - Bring your own AI model or host it locally
- **Visualizes changes** - See and checkpoint your code modifications
- **Runs AI agents** - Let AI work on your entire codebase, not just individual files

## Quick Start

After cloning this repository, follow these steps to build and run Textab:

### Prerequisites

**macOS/Linux:**
```bash
# Ensure you have Node.js 20.18.2 (recommended: use nvm)
nvm install 20.18.2
nvm use 20.18.2
```

**Windows:**
- Install [Visual Studio 2022 Community](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community)
- In Visual Studio Installer, select:
  - `Desktop development with C++`
  - `Node.js build tools`

### Build and Run

```bash
# 1. Install dependencies
npm install

# 2. Build Textab (takes ~5 minutes)
npm run watch

# 3. Run Textab
# On macOS/Linux:
./scripts/code.sh

# On Windows:
./scripts/code.bat
```

That's it! Textab will launch in a new window. Press `Ctrl+R` (or `Cmd+R` on Mac) to reload the window after making changes to the code.

## Links

- 🌐 [Website](https://textab.github.io)



## Support

- Join our [Discord server](https://discord.gg/RSNjgaugJs)
- Email us: hello@textabeditor.com

---

*Textab is a fork of the [VS Code](https://github.com/microsoft/vscode) repository, enhanced with AI capabilities and privacy-focused features.*
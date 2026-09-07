# Qwen Code Companion (personal fork)

> [!NOTE]
> This is a **personal fork** of [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) maintained by [luskyle](https://github.com/luskyle). The extension source lives in `packages/vscode-ide-companion`. This fork is **not published** to the VS Code Marketplace or Open VSX — build it from source as described below, or use the [official release](https://marketplace.visualstudio.com/items?itemName=qwenlm.qwen-code-vscode-ide-companion) from upstream.

[![Fork](https://img.shields.io/badge/fork-luskyle%2Fqwen--code-181717?logo=github)](https://github.com/luskyle/qwen-code)

Seamlessly integrate [Qwen Code](https://github.com/QwenLM/qwen-code) into Visual Studio Code with native IDE features and an intuitive chat interface. This extension bundles everything you need — no additional installation required.

## Demo

<video src="https://cloud.video.taobao.com/vod/IKKwfM-kqNI3OJjM_U8uMCSMAoeEcJhs6VNCQmZxUfk.mp4" controls width="800">
  Your browser does not support the video tag. You can open the video directly:
  https://cloud.video.taobao.com/vod/IKKwfM-kqNI3OJjM_U8uMCSMAoeEcJhs6VNCQmZxUfk.mp4
</video>

## Features

- **Native IDE experience**: Dedicated Qwen Code Chat panel accessed via the Qwen icon in the editor title bar
- **Native diffing**: Review, edit, and accept changes in VS Code's diff view
- **Auto-accept edits mode**: Automatically apply Qwen's changes as they're made
- **File management**: @-mention files or attach files and images using the system file picker
- **Conversation history & multiple sessions**: Access past conversations and run multiple sessions simultaneously
- **Open file & selection context**: Share active files, cursor position, and selections for more precise help

## Requirements

- Visual Studio Code 1.96.0 or newer (also works with Cursor, Windsurf, and other VS Code-based editors)

## Quick Start

1. **Build from source** (this fork is not published to a registry):

   ```bash
   git clone https://github.com/luskyle/qwen-code.git
   cd qwen-code/packages/vscode-ide-companion
   npm install
   npm run package   # produces qwen-code-vscode-ide-companion-*.vsix
   ```

2. **Install the VSIX** — in VS Code, run `Extensions: Install from VSIX...` and pick the generated `.vsix` file.

3. **Open the Chat panel** using one of these methods:

   - Click the **Qwen icon** in the top-right corner of the editor
   - Run `Qwen Code: Open` from the Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)

4. **Start chatting** — Ask Qwen to help with coding tasks, explain code, fix bugs, or write new features

## Commands

| Command                          | Description                                            |
| -------------------------------- | ------------------------------------------------------ |
| `Qwen Code: Open`                | Open the Qwen Code Chat panel                          |
| `Qwen Code: Run`                 | Launch a classic terminal session with the bundled CLI |
| `Qwen Code: Accept Current Diff` | Accept the currently displayed diff                    |
| `Qwen Code: Close Diff Editor`   | Close/reject the current diff                          |

## Feedback & Issues

- 🐛 Fork-specific issues: [luskyle/qwen-code issues](https://github.com/luskyle/qwen-code/issues)
- 💡 Feature bugs & requests: please report to the upstream project — [QwenLM/qwen-code issues](https://github.com/QwenLM/qwen-code/issues/new?template=bug_report.yml&labels=bug,vscode-ide-companion)
- 📖 [Documentation](https://qwenlm.github.io/qwen-code-docs/)
- 📋 [Changelog](https://github.com/QwenLM/qwen-code/releases)

## Contributing

We welcome contributions! See our [Contributing Guide](https://github.com/QwenLM/qwen-code/blob/main/CONTRIBUTING.md) for details on:

- Setting up the development environment
- Building and debugging the extension locally
- Submitting pull requests

## Terms of Service and Privacy Notice

By installing this extension, you agree to the [Terms of Service](https://qwenlm.github.io/qwen-code-docs/en/users/support/tos-privacy/).

## License

[Apache-2.0](https://github.com/QwenLM/qwen-code/blob/main/LICENSE)

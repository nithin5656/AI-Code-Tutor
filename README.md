# AI Code Tutor

**AI Code Tutor** is a powerful VS Code extension designed to boost developer productivity and accelerate learning. Acting as your personal AI sidekick, it helps you understand complex code snippets instantly without leaving your editor.

## 🚀 Features

### 1. Explain Code
Select any block of code in your editor and ask AI Code Tutor to explain it.
- **How to use:** Highlight code > Open Command Palette (`Ctrl+Shift+P`) > Run `Explain Code`.
- **Result:** You receive a concise explanation of what the selected code does.

*(Note: Currently in v0.0.1, this feature displays a mock analysis message. Integration with LLM APIs is the next step.)*

## 🛠️ Installation

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Press `F5` to launch a new VS Code window with the extension loaded.

## 📖 How to Use

1. **Select Code:** Open a file and highlight the code snippet you want to understand.
2. **Run Command:**
   - Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac).
   - Type `Explain Code` and select `AI Code Tutor: Explain Code`.
3. **View Explanation:** An information message will appear with the explanation (currently a placeholder).

## ⚙️ Extension Settings

*Currently no configurable settings.*

*Planned for upcoming releases:*
- `aiCodeTutor.apiKey`: Set your OpenAI/Gemini API key.
- `aiCodeTutor.model`: Choose your preferred AI model (e.g., GPT-4, Claude, Gemini).

## 📅 Roadmap

- [x] Basic extension scaffolding
- [x] "Explain Code" command registration
- [ ] Integration with OpenAI / Google Gemini API
- [ ] Markdown-formatted responses in a side panel (Webview)
- [ ] "Refactor Code" command
- [ ] Unit generation support

## 📝 Release Notes

### 0.0.1
- Initial release.
- Added `Explain Code` command foundation.
- Basic TypeScript architecture setup.

## 🤝 Contributing

Contributions are welcome!
1. Fork the repo.
2. Create a feature branch (`git checkout -b feature/amazing-feature`).
3. Commit your changes.
4. Open a Pull Request.

## 📄 License

This project is licensed under the MIT License.

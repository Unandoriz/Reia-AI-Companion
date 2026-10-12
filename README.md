<div align="center">

<img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/icon.png" width="112" alt="Reia">

# Reia

**An AI companion that lives on your computer.**<br>
She talks, remembers, changes over time — and can step out of the window onto your desktop.

<a href="https://github.com/Unandoriz/Reia-AI-Companion"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/buttons/lang-en-on.svg" alt="English"></a>
<a href="https://github.com/Unandoriz/Reia-AI-Companion/blob/site/README_RU.md"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/buttons/lang-ru-off.svg" alt="Русский"></a>

<br>

<a href="https://github.com/Unandoriz/Reia-AI-Companion/releases/latest"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/buttons/download-en.svg" alt="Download for Windows"></a>
<a href="https://discord.gg/yxjzyfT3hP"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/buttons/discord.svg" alt="Discord"></a>
<a href="https://github.com/Unandoriz/Reia-AI-Companion/blob/main/SUPPORT.md"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/buttons/support-en.svg" alt="Support the project"></a>

<br>

[![Latest version](https://img.shields.io/github/v/release/Unandoriz/Reia-AI-Companion?label=version&color=c4917a)](https://github.com/Unandoriz/Reia-AI-Companion/releases/latest)
![Windows 10 · 11](https://img.shields.io/badge/Windows-10%20·%2011-2b2522)
![Interface: English · Русский](https://img.shields.io/badge/interface-English%20·%20Русский-2b2522)
![Free](https://img.shields.io/badge/price-free-2b2522)

<br>

<img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/screenshots/chat.png" alt="A conversation with Reia: the chat on the left, her 3D avatar on the right" width="100%">

</div>

## What is Reia

Reia is a desktop companion with a living 3D avatar. You give her a character — a name,
a personality, a manner of speech — and talk to her by text or by voice. She answers aloud
with matching lip movement and facial expressions, remembers what you told her weeks ago,
keeps a diary, and her mood and attitude towards you shift with how your conversations go.

She can run **entirely on your machine**: a local language model, local speech synthesis
and recognition, a local database. Nothing leaves your computer unless you choose a cloud
model. When you want her closer, she steps out of the app window and stands right on your
desktop, on top of your other windows.

## Features

### 💬 Characters and conversations
- **Character cards** with description, personality, greetings and example dialogues;
  import **Character Card V2/V3** PNG cards, export your own with the avatar included.
- **Lorebooks** — notes about the character's world that enter the prompt only when they come up.
- Streaming replies, editing, deleting, **regenerate with variants**, continue a cut-off answer.
- Long conversations are **summarised** instead of silently cut; a live token counter shows
  how much of the context a card takes.

### 🧠 Memory and personality
- **Long-term memory** on local embeddings: she writes down what is worth remembering about
  you and recalls it when the subject comes up.
- A **diary** where she reflects on your conversations.
- **Traits that change over time** — affection, trust, energy, mood, annoyance. She gets
  tired after long talks, rests, gets bored when you are away — and may **speak first**
  when you come back.

### 🎭 Avatar
- Any **VRM** model; two come bundled.
- **Lip sync** from the voice, **emotions** that follow the meaning of the reply,
  blinking, breathing, small idle movements.
- Her **eyes follow your cursor**; ask her to smile, wink or close her eyes — she will.
- Camera angle, zoom and background are remembered per conversation.

### 🖥️ On your desktop
- A frameless, always-on-top window with just her in it; transparent areas let your clicks through.
- **Subtitles** under her, a text field on hover, voice input.
- Call her **by name** instead of pressing a key.
- She can step aside for fullscreen games and videos, and has a right-click menu of quick actions.

### 🎙️ Voice
- Speech synthesis: **Piper** (fast, on the processor, many languages), **Qwen3-TTS**
  (on the graphics card, **clones a voice from a short sample**), **OpenAI**-compatible
  endpoints, **ElevenLabs**, or the Windows system voice.
- She starts speaking from the first sentence, without waiting for the whole reply.
- Speech recognition with **whisper.cpp** and Silero VAD; push-to-talk on a global hotkey
  or a mouse side button; your choice of microphone and speakers.

### ⚙️ Models: local or cloud
- **Local** models through **llama.cpp** — the app installs the right build for your
  hardware (CUDA, Vulkan or processor-only) and keeps it updated.
- It **detects your hardware**, suggests a model that fits, browses **Hugging Face**
  with a fit mark on every file and forecasts video memory before you start.
- **Cloud**: OpenAI, Anthropic, OpenRouter, DeepSeek, Grok, Qwen, Z.AI, Gemini or any
  OpenAI-compatible endpoint — with a **monthly spending limit**.
- Sampling presets, a thinking mode for reasoning models, HTTP and SOCKS5 proxy support.

### 🛠️ She can do things
- Built-in tools: time, **web search**, weather, opening links and apps, media controls,
  clipboard, files, **reminders**, system info.
- Connect your own tools through **MCP servers**.
- **Multi-step errands**: she looks at the screen, clicks and types to get a task done.
- Anything that changes the world outside the app asks your permission first.

### 👁️ Vision (optional)
- Turn it on, and she sees your screen when you talk to her — ask “what's on my screen?” —
  and while she works on an errand.
- You choose the monitor and how often frames are taken, and list apps she must never look
  at (password managers, banking); a visible indicator and one switch turn it all off.

### 📱 And more
- A **built-in web server**: chat with her from your phone on the same network, protected by a PIN and a QR code.
- **Themes**: light and dark, ready-made sets, your own theme saved to a file; chat fonts,
  bubbles, density and backgrounds.
- **Your data stays yours**: everything in a local database, API keys encrypted by Windows,
  automatic backups, full export and import, a portable version.
- **Updates itself**: it learns about new versions from this page and installs them on a click.

## Screenshots

<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/screenshots/desktop.png" alt="Reia standing on the desktop next to the app window, with a subtitle under her"></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/screenshots/character.png" alt="The character editor"></td>
  </tr>
  <tr>
    <td align="center">On the desktop, with subtitles</td>
    <td align="center">Character editor</td>
  </tr>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/screenshots/hardware.png" alt="Hardware detection and load presets"></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/Unandoriz/Reia-AI-Companion/site/assets/screenshots/voices.png" alt="Speech engines and the voice catalogue"></td>
  </tr>
  <tr>
    <td align="center">Hardware detection and load presets</td>
    <td align="center">Voices</td>
  </tr>
</table>

## Getting started

1. Download **`Reia_<version>_x64-setup.exe`** from the [latest release](https://github.com/Unandoriz/Reia-AI-Companion/releases/latest)
   and run it. No administrator rights are needed: Reia installs into your user folder.
2. Windows may complain about the installer — that's fine.
3. On first launch a short wizard asks for the language and whether she should think
   on your machine or through the cloud, and suggests a model that fits your hardware.
4. Create a character (or import a card), start a conversation — and when you like,
   put her on the desktop from the **Companion** tab.

> [!TIP]
> Prefer not to install? Take **`Reia_<version>_x64-portable.zip`** from the same release,
> unpack it anywhere you can write to and run `reia.exe`. All its data stays in the `Data`
> folder next to it.

## System requirements

**Windows 10 or 11, 64-bit.** Everything else depends on where the model runs:

| Your machine | What runs well locally |
|---|---|
| No dedicated graphics card | a 4B model on the processor, Piper voice |
| 6–8 GB of video memory | 8–12B models, Qwen3-TTS on the graphics card |
| 12 GB of video memory or more | 12–32B models, your own cloned voice, vision |
| Any computer with internet | cloud models with your API key |

NVIDIA cards run through CUDA, other cards through Vulkan. Models take a few gigabytes
of disk each; the app shows the size and whether a file fits before you download it.

## FAQ

<details>
<summary><b>Is it free?</b></summary>

Yes. Local models cost nothing. Cloud models are paid to their provider by your own key,
and Reia can stop requests when a monthly limit is reached.
</details>

<details>
<summary><b>Does it need the internet?</b></summary>

Only to download models and updates — or if you choose a cloud model or web search.
A local setup works offline.
</details>

<details>
<summary><b>Where are my conversations stored?</b></summary>

On your computer, in a local database. Keys to cloud services are encrypted by Windows and
never leave the app. Backups are made automatically and you can export everything into one file.
</details>

<details>
<summary><b>Can I use my own avatar?</b></summary>

Yes — any VRM model. Put it into the models folder (the character editor has a button that
opens it) and choose it in the character card.
</details>

## Community

- **[Discord](https://discord.gg/yxjzyfT3hP)** — questions, bug reports, ideas and screenshots of your companions.
- **[Issues](https://github.com/Unandoriz/Reia-AI-Companion/issues)** — if something is broken, describe what you did and what happened.
- **[Support the project](https://github.com/Unandoriz/Reia-AI-Companion/blob/main/SUPPORT.md)** — Reia is made by one person, and every bit of help keeps it growing.

## Built with

[Tauri](https://tauri.app) ·
[three-vrm](https://github.com/pixiv/three-vrm) ·
[llama.cpp](https://github.com/ggml-org/llama.cpp) ·
[whisper.cpp](https://github.com/ggml-org/whisper.cpp) ·
[Piper](https://github.com/rhasspy/piper) ·
Qwen3-TTS ·
[Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync) ·
[eSpeak NG](https://github.com/espeak-ng/espeak-ng) ·
[Silero VAD](https://github.com/snakers4/silero-vad) ·
[ONNX Runtime](https://onnxruntime.ai)

<sub>This repository hosts Reia's releases. The app checks this page for new versions and updates itself from here.</sub>

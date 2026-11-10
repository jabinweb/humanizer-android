# Humanizer for Android

[![Latest release](https://img.shields.io/github/v/release/jabinweb/humanizer-android?label=latest&color=2354D9)](https://github.com/jabinweb/humanizer-android/releases/latest) · [Changelog](CHANGELOG.md) · versions follow [SemVer](https://semver.org)

Make AI-written text sound human — write, humanize and polish, on your phone.

**[⬇ Download the full app](https://github.com/jabinweb/humanizer-android/releases/latest/download/Humanizer.apk)** · Android 8.0+ (arm64) · ~28 MB — runs AI models on your phone

**[⬇ Download Lite](https://github.com/jabinweb/humanizer-android/releases/latest/download/Humanizer-Lite.apk)** · Android 8.0+ (any phone) · ~1.5 MB — no on-phone AI; use the built-in engine, Ollama on your Wi-Fi, or your own API key

## What it does
- **Studio** — paste text, pick a tone and strength, see an AI-likelihood score before → after, with a word-level diff and highlighted AI-sounding phrases.
- **Attach files & images** — text, Word, PDF and photos (to models that can see images), plus voice input and sharing into the app from any other app.
- **Chat first** — ask it to write something, then keep going: *"humanize this"*, *"shorter"*, *"summarize"*, *"translate to Spanish"*.
- **Humanize anywhere** — select text in any app and choose **Humanize** from the selection menu, then replace it in place.
- **AI on your phone** — download Qwen, DeepSeek-R1, Phi-4 mini or TinyLlama and run them fully offline. The app reads your phone's RAM and storage and tells you which will run well. Downloads are resumable and checksum-verified.
- **Privacy Shield** — emails, phone and card numbers, IDs and API keys are masked on your phone before text goes to any cloud AI, then restored in the answer.
- **Checks that run on-device** — reading level, "needs a source" flags for statistics and citations, and a writing receipt (hashed, timestamped record of your edits).
- **Your engine, your choice** — a free built-in engine, Ollama running on your own computer (auto-discovered on your Wi-Fi), or your own OpenAI / Anthropic / Gemini / OpenRouter key.
- **Write like me** — learns your style from a sample of your writing.
- **Accounts & sync** — optional email + password; syncs history and voice with the web app. API keys never leave your phone.

## Install
1. Download `Humanizer.apk` above on your phone.
2. Open it. Android will ask you to allow installs from your browser/files app — this is normal for apps outside the Play Store.
3. Open **Humanizer**.

## Versions
Every release is tagged `vMAJOR.MINOR.PATCH` and ships versioned files — `Humanizer-1.4.0.apk` (full) and `Humanizer-1.4.0-lite.apk` — plus unversioned aliases (`Humanizer.apk`, `Humanizer-Lite.apk`) that always point to the newest. Pick a specific version from [Releases](https://github.com/jabinweb/humanizer-android/releases) if you need to pin or roll back.

## Verify your download (optional)
SHA-256 of the APK is in `Humanizer.apk.sha256`. The app is signed with this certificate (SHA-256):

```
349560b1e6c5ccc7f2840c1cb38d65b7c37e745ee76495e23de10458fc421e53
```

## Privacy
Text is sent only to the engine you pick. API keys are stored encrypted on your phone. This repository contains releases only.

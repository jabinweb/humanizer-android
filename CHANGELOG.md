# Changelog

All notable changes to Humanizer. Format: [Keep a Changelog](https://keepachangelog.com), versioning: [Semantic Versioning](https://semver.org).
The web app, server and Android app share one product version. Android `versionCode` increases by one every release.

## [1.5.0] — 2026-11-11 · Android versionCode 7
### Added
- Tools tab: 18 one-tap jobs (cover letter, meeting → actions, summarize, flashcards, quiz, reply in context, tone check…) and offline Redact & restore / Text checks.
- Fix by sentence: AI-sounding sentences flagged with the reason, rewritten one at a time.
- Privacy router and Privacy tab: sensitive text stays on your phone / computer instead of a cloud engine.
- Standard Material 3 bottom navigation; Settings moved to a header gear.
### Changed
- Back goes up one level instead of closing the app; open tool kept across tabs.
- Account/server errors no longer say "invalid key".

## [1.4.0] — 2026-11-10 · Android versionCode 6
### Fixed
- The AI no longer just echoes your message back: follow-ups were sent to the model as the *previous answer* instead of the new message.
- Thinking models on Ollama (qwen3, DeepSeek-R1) no longer look frozen — their reasoning field is now handled. Reasoning is off by default so replies are immediate.
### Added
- Real conversation mode: chat with memory of earlier turns. Write and Humanize still trigger automatically (or pick Chat / Write / Humanize).

## [1.3.0] — 2026-11-10 · versionCode 5
### Added
- "Show model reasoning" toggle for thinking models (web + Android).
- Android downloads resume automatically after a connection loss; web model downloads (browser and Ollama) resume too.
- Web: download and remove models inside your own Ollama, with progress and a hardware-fit check.
### Fixed
- Web: recovery from WebGPU device loss, serialized GPU operations, smaller GPU memory footprint, optional Compatibility mode, and the app shell is no longer cached.

## [1.2.0] — 2026-11-10 · versionCode 4
### Added
- File and image attachments in chat (text, Word, PDF, photos), model-aware image support, share-into-app, voice input, ChatGPT-style input box.
- "Get started" card; **Full** (~28 MB, on-phone AI) and **Lite** (~1.5 MB) Android builds.

## [1.1.0] — 2026-11-10 · versionCode 3
### Added
- Chat-first layout; AI models that run on the phone (Qwen, DeepSeek-R1, Phi-4 mini, TinyLlama) with hardware-fit guidance and verified downloads.
- Privacy Shield, reading level, "needs a source" flags, writing receipts, quick tools.

## [1.0.1] — 2026-11-10 · versionCode 2
### Fixed
- Clear message instead of a raw 400 when the built-in engine is not switched on.

## [1.0.0] — 2026-11-10 · versionCode 1
- First release: Studio, Chat, History, engines (built-in, Ollama on Wi-Fi, bring-your-own API key), accounts and sync.

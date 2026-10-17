<p align="center">
  <img src="https://voicevibe.ai/static/icons/voicevibe-512.png" alt="VoiceVibe" width="112" height="112">
</p>

<h1 align="center">VoiceVibe</h1>

<p align="center">
  <b>Talk to your computer. It types, speaks & does what you ask.</b><br>
  Free, unlimited voice typing that runs on your device, offline. AI voice modes with Pro.<br>
  Windows · macOS · Linux (X11)
</p>

<p align="center">
  <a href="https://voicevibe.ai/download?utm_source=github&utm_medium=readme"><b>Download</b></a> ·
  <a href="https://voicevibe.ai/getting-started">Getting started</a> ·
  <a href="https://voicevibe.ai/faq">FAQ</a> ·
  <a href="https://github.com/VoiceVibe-AI/voicevibe/issues">Issues</a>
</p>

---

VoiceVibe is an AI voice assistant that works with any app or website on
your computer. Press a key and say what you need. Dictate, rewrite, chat,
generate images, hear text read aloud, launch agents. While you speak,
choose where it goes: type it, ask the assistant, ask about what's on your
screen or the selected text, transform text, or hand a task to an AI chat
or coding agent. Do more without losing your train of thought.

> **About this repository.** VoiceVibe's public home on GitHub: the
> getting-started guide and the issue tracker for bugs and feature requests.

## Contents

- [What you get](#what-you-get)
- [Free, Pro and Pro Max](#free-pro-and-pro-max)
- [Platforms and system requirements](#platforms-and-system-requirements)
- [Getting started](#getting-started)
- [Privacy](#privacy)
- [Reporting bugs and requesting features](#reporting-bugs-and-requesting-features)

## What you get

**How it works:** optionally select text or files, hold your shortcut key,
speak, pick a mode and inputs, release. Push-to-talk (hold to speak) and
toggle (press to start, press again to stop) are both available. Each
mode can have its own shortcut. VoiceVibe is not always listening: you
start every recording.

| Mode | What it does | Plan |
|---|---|---|
| Voice Typing | Speech-to-text in any text field. On-device with Parakeet, 100% offline. Includes Word Replacements. | Free |
| Magic Typing | Create or transform text in any app: "make this more professional", "translate to Spanish". | Pro |
| Magic Clipboard | Like Magic Typing, but the result goes to your clipboard instead of replacing anything. | Pro |
| Voice Assistant | Ask questions with spoken answers and follow-ups; can search the web for current information. Conversations are saved on your device, not on our servers. | Pro |
| Text-to-Speech | Read selected text aloud; 120 preset voices, 0.75x–2.0x speed, WAV export, up to 3 voice clones (with permission). | Pro |
| AI Images | Create new images or edit existing ones. | Pro |
| Note Taker | Turn speech and files into structured notes saved in Documents/VoiceVibe Notes. | Pro |
| Chat Launcher | Prepare a prompt and context for ChatGPT, Claude, Gemini, Perplexity or a custom HTTPS URL; you review and send it. | Pro |
| Agent Launcher | Dictate, review and launch tasks for Claude Code, Codex CLI, Cursor, OpenCode or Pi. Availability varies by platform. | Pro |
| Add to Dictionary | Teach VoiceVibe names and terms, reviewed before saving. | Pro |

**Context you can add while speaking (Pro modes):** selected text,
clipboard content, a partial or full screenshot, and supported files.
Available inputs depend on the mode.

Chat and coding tools keep their own accounts and subscriptions; a
VoiceVibe plan does not include them. AI output can contain errors.

## Free, Pro and Pro Max

| | Free | Pro | Pro Max |
|---|---|---|---|
| Price | $0 | $14.99/month, or $143.90/year | $29.99/month, or $287.90/year |
| Voice Typing | Unlimited, on-device, 100% offline, 25 languages | Adds cloud cleanup of grammar, filler words and self-corrections; 100 cloud speech languages | Same as Pro |
| Other modes | – | All Pro modes | All Pro modes, four times the usage allowance |
| Account | Not needed | Required | Required |
| Devices | One device | Up to 3 (Windows, macOS and Linux can be mixed) | Up to 3 |

- **Pro modes run on cloud AI and need an internet connection.** Pro
  Voice Typing can work offline with the Local Model or Cloud with Local
  Fallback setting.
- Paid usage is generous but not unlimited. Allowances reset monthly,
  also on annual billing. When an allowance runs out, Free Voice Typing
  keeps working.
- **Pro Preview:** choose "Try Pro" in the app to try the Pro modes with a
  small usage allowance. An account is needed, a credit card is not. AI
  Images is not included. It is usage-based, not a timed trial.
- No API keys on any plan.
- 7-day money-back guarantee on Pro subscriptions. Cancel anytime from
  your dashboard.

Checkout shows the final total, including any taxes. Full details:
[pricing](https://voicevibe.ai/pricing) ·
[Free vs Pro comparison](https://voicevibe.ai/comparison).

## Platforms and system requirements

| Platform | Supported | Not supported | Download |
|---|---|---|---|
| Windows | Windows 10 or later, Intel/AMD x86-64 | Windows on ARM | Installer (.exe) |
| macOS | Apple Silicon (M1 or newer), macOS 14 or later | Intel Macs | DMG |
| Linux | x86-64 with an X11 session; audio via PulseAudio or ALSA. Linux Mint is our initial QA target. | Wayland (including XWayland), ARM Linux | .deb or AppImage |

Current versions and file sizes are on the
[download page](https://voicevibe.ai/download?utm_source=github&utm_medium=readme).

**Minimum:** 4 GB RAM, 3 GB free storage for the app plus the local
model, and a microphone. Pro also needs an internet connection.
**Recommended:** 8 GB RAM, a dedicated USB microphone and a modern
multi-core processor.

**Memory and disk:** with the on-device model loaded (Free), VoiceVibe
uses about 2.7 GB of RAM and about 2.9 GB of disk. With the model
unloaded (Pro), about 320 MB each. First offline use of Voice Typing
downloads the Parakeet model.

## Getting started

[Download VoiceVibe](https://voicevibe.ai/download?utm_source=github&utm_medium=readme)
for your platform. No account is needed for free Voice Typing. The full
guide is at [voicevibe.ai/getting-started](https://voicevibe.ai/getting-started).

<details>
<summary><b>Windows</b></summary>

1. Run the `.exe` installer and follow the wizard.
2. If Windows SmartScreen appears, click **More info**, then **Run
   anyway**, but only for an installer downloaded from voicevibe.ai. This
   can happen while a new Windows app builds download reputation.
   Windows Defender may briefly scan VoiceVibe on first run.
3. Launch VoiceVibe from the Start menu. The microphone permission is
   granted automatically or asked for on first use.
4. Open any text field (Notepad, Word, a browser), **hold Right Ctrl**,
   say "Hello, this is a test", and release.

</details>

<details>
<summary><b>macOS</b></summary>

1. Open the `.dmg` and drag VoiceVibe to Applications.
2. Open VoiceVibe from Applications. If macOS shows a first-launch
   security prompt, use **Open** or **Open Anyway**, but only for an
   installer downloaded from voicevibe.ai.
3. Grant permissions when asked (System Settings › Privacy & Security):
   - **Accessibility**: global keyboard shortcuts (first launch)
   - **Microphone**: voice input (first recording)
   - **Screen Recording**: screenshot features in Pro modes
   - **Automation**: typing into other apps (first text insertion)

   You may need to restart VoiceVibe after granting them.
4. Open any text field (Notes, TextEdit, a browser), **hold Right Ctrl
   (⌃)**, say "Hello, this is a test", and release.

</details>

<details>
<summary><b>Linux (x86-64, X11)</b></summary>

1. Check your session and architecture:
   ```sh
   echo $XDG_SESSION_TYPE   # expected: x11
   uname -m                 # expected: x86_64
   ```
   On Wayland, switch to an X11 session at the login screen.
2. Install one package:
   ```sh
   # .deb (best fit for Linux Mint and similar apt-based systems)
   sudo apt install ./voicevibe_*.deb

   # AppImage (portable)
   chmod +x VoiceVibe-*.AppImage
   ./VoiceVibe-*.AppImage
   ```
3. Open any text field (terminal, text editor, browser), **hold Right
   Ctrl**, say "Hello, this is a test", and release.

</details>

**After the first test:**

- Change the shortcut or switch between push-to-talk and toggle in
  Settings.
- Fix words that come out wrong with **Word Replacements** (for example
  "voice vibe" → "VoiceVibe").
- If words are missed, check that the right microphone is the default
  input and that its level is clear but not clipping, then restart
  VoiceVibe.
- Choose **Try Pro** in the app to try the other modes.
- VoiceVibe tells you when an update is available; updates are never
  installed without your permission.

More help: [FAQ](https://voicevibe.ai/faq) ·
[support](https://voicevibe.ai/support).

## Privacy

- **Free Voice Typing runs entirely on your device.** Voice audio and
  transcription stay on your computer, offline. Free sends only a
  pseudonymous device identifier and a daily usage count, with no voice
  audio, dictated text or personal content. Crash reporting is on by
  default and can be turned off in Settings › Privacy.
- **Pro modes use the cloud.** Audio and the context you include are sent
  for processing, encrypted in transit and processed transiently. Pro
  Voice Typing and Magic Typing also send a limited amount of text around
  your cursor and the app and window name.
- VoiceVibe does not sell your data or use your content to train AI
  models.
- For sensitive work, use Free Voice Typing.

Details: [privacy policy](https://voicevibe.ai/privacy) ·
[privacy FAQ](https://voicevibe.ai/faq).

## Reporting bugs and requesting features

- **Bugs and feature requests:** [open an issue](https://github.com/VoiceVibe-AI/voicevibe/issues/new/choose),
  or use the [feedback form](https://voicevibe.ai/feedback) if you prefer
  not to post publicly. Please search existing issues first.
- **Logs** help a lot. They are in `~/.local/share/voicevibe/logs/`
  (Linux), `~/Library/Logs/VoiceVibe/` (macOS) and
  `%LOCALAPPDATA%\VoiceVibe\Logs\` (Windows). Read them before posting
  and remove anything private: this tracker is public.
- **Pro and Pro Max subscribers:** for account and billing help, request
  priority support from your account dashboard.
- **Security issues:** please don't open a public issue. See
  [SECURITY.md](SECURITY.md).

---

© VoiceVibe. All rights reserved. VoiceVibe is proprietary software; see
the [terms](https://voicevibe.ai/terms).

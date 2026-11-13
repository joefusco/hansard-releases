# Hansard

A macOS meeting copilot. It listens to your calls, transcribes them on your Mac, and uses Claude
to answer questions, surface useful context and write up the meeting when it ends.

This repository only hosts downloads. Grab the latest `Hansard.app` from
[Releases](https://github.com/joefusco/hansard-releases/releases/latest). Hansard checks here for
updates and installs them itself.

## Requirements

- A Mac with Apple silicon (M1 or later), macOS 14.4 or later
- [Claude Code](https://claude.com/claude-code), installed and signed in (`claude` in Terminal)

## First launch

Hansard isn't notarized by Apple yet, so macOS blocks it the first time:

1. Unzip, and drag `Hansard.app` into Applications.
2. Right-click `Hansard.app` → **Open** → **Open**. (Or: System Settings → Privacy & Security → **Open Anyway**.)
3. Follow the setup window: it checks Claude Code, asks for microphone and system audio
   permission, and downloads the speech models (about 500 MB).

## Privacy

Audio, voiceprints and screenshots stay on your Mac. Transcript text is sent to Claude through
your own Claude Code account. Check local rules before recording a conversation, and tell the
people you're meeting with.

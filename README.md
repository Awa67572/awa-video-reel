# awa-video-reel

A free Claude Code skill by Awa K. Penn that edits your short videos so every visual and sound lands on the words you say.

**[Download awa-video-reel.zip](https://github.com/Awa67572/awa-video-reel/releases/latest/download/awa-video-reel.zip)**

## What it does

Drop in a video (up to 1 minute) and type `/awa-video-reel`. It adds:

- face-tracked effects (stamps, toggles, phone fans, checklists and more)
- captions with your keywords highlighted, plus title, stat, list and call-to-action cards
- punch-ins, a slow push and an optional cinematic look
- music that dips under your voice, and a sound on every change
- website b-roll: mention a site and it asks if you want it recorded, then opens it in Chrome and scrolls and clicks with a visible cursor
- an optional "Follow for more" card with your handle

It shows you the plan first and renders only after you say yes. You get two MP4s: one with music, one without.

## Install (3 steps)

1. Download and unzip `awa-video-reel.zip`.
2. Copy the `awa-video-reel` folder into `~/.claude/skills/`.
3. Restart Claude Code, drag in a video and type `/awa-video-reel`.

Or open Claude Code and paste: "Install the skill in this folder: [path to the unzipped folder]. Follow its INSTALL.md."

You also need Google Chrome (or Edge), Node.js 20+, Python 3.11 or 3.12 and ffmpeg. The full list and tips are in `INSTALL.md` inside the zip.

## Credits

Effects engine: MIT licence (`effects/LICENSE` in the zip). Captions, cards and b-roll layout: HyperFrames by HeyGen. Cards: Remotion. Sound effects: Pixabay. Music: CC0 and one CC BY track, listed in `music/CREDITS.md`.

Learn AI for free in my newsletter: [awa-newsletter.beehiiv.com/subscribe](https://awa-newsletter.beehiiv.com/subscribe)

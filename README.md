# Bonsai Capture — Landing Page

Marketing and install guide site for [Bonsai Capture](https://github.com/TeeLapo6/bonsai-capture-ext), a Chrome extension that captures AI conversations and their artifacts locally.

## Live Site

[https://taylorlaporte.engineer/Bonsai-Capture/](https://taylorlaporte.engineer/Bonsai-Capture/)

Hosted via GitHub Pages from the `main` branch of this repo.

## What this site covers

- Hero overview of the extension
- Feature grid: multi-provider capture, artifact capture, structured exports, provenance
- Real screenshot showcase (Gemini, ChatGPT, Claude captures)
- Step-by-step load-unpacked install guide
- Pro / background sync future roadmap section

## Supported providers (as of alpha v0.1.0)

- ChatGPT (`chatgpt.com`, `chat.openai.com`) — conversations, images, Deep Research, Canvas
- Claude (`claude.ai`) — conversations, code artifacts, documents, canvas captures
- Gemini (`gemini.google.com`) — conversations, images, video, immersive artifacts, Deep Research
- Grok (`grok.com`) — conversations
- Jules (`jules.google.com`) — task outputs, code artifacts

## Development

This is a static HTML site using Tailwind CSS via CDN. No build step required.

```bash
# Serve locally with any static server, e.g.
npx serve .
# or just open index.html in a browser
```

All showcase screenshots live in `assets/showcase/`.

## Linking to the extension

The extension source is at: [https://github.com/TeeLapo6/bonsai-capture-ext](https://github.com/TeeLapo6/bonsai-capture-ext)

The install guide on this site walks users through:
1. Cloning or downloading the extension repo
2. Running `npm install && npm run build`
3. Loading `dist/` as an unpacked extension in Chrome or Brave

## Deploying

Push to `main` — GitHub Pages publishes automatically from the root of this branch.

```bash
git add -A && git commit -m "chore: update landing page" && git push origin main
```

---

**Bonsai Capture | Keep your AI conversations.**

# wj's birthday project

Files included:

- index.html — landing page (appears at the site root)
- happy.html — birthday message page with animated confetti and an embedded heart decoration; includes audio playback if you add jealous.mp3 to the repo root
- surprise.html — 12-hour persistent timer page

Important setup:

1. Add the GIF file you saved (milkmochabear.gif) to the repository root so the landing page shows the animation.
2. If you want background audio to play on happy.html, add an MP3 named jealous.mp3 to the repository root (only include files you own the rights to).

Deploying with GitHub Pages:

1. After pushing these files to the repository, go to Settings → Pages in the GitHub UI and set the Source to:
   - Branch: main
   - Folder: / (root)

2. Wait a minute or two, then the site should be available at:
   https://arunekoo.github.io/wj-birthday-project/

Notes:
- Filenames are case-sensitive on some hosts — be sure to name the GIF exactly milkmochabear.gif and the audio jealous.mp3 if you include them.
- If autoplay of the audio is blocked by the browser, interacting with the page (click/tap) will start playback.

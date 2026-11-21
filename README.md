# 🎵 Catch the Notes

**A browser arcade game starring your face.**

You're on stage. Catch the 🎵 notes (+10), grab the ⭐ stars for bonus points (+50),
and dodge the 🚫 copyright strikes (−1 life, you get 3). Chain catches for a combo
multiplier up to **x5** — but miss a note and the combo resets. The tempo ramps up
every level. How long can you stay on stage?

## Play

Open **https://1kingcason-bot.github.io/catch-the-notes/** in any browser — no install, no account.

It's also an installable PWA: on desktop or phone, use your browser's
**Install app / Add to Home Screen** option to play it like a native app.

## Controls

| Action | Keys |
| --- | --- |
| Move | ← → or A / D, or move the mouse |
| Start / restart | Enter, Space, or click |
| Pause | P or Esc |
| Mute | M |

## Run locally

No build step — it's plain HTML/JS/CSS.

```powershell
python -m http.server 8765
# then open http://localhost:8765/
```

(Opening `index.html` directly also works, but the offline cache only
activates over http/https.)

## Credits

- Code, design & headliner: **you** 🎤
- Built with vanilla JavaScript, Canvas 2D, Web Audio, and zero dependencies.

© 2026 Catch the Notes

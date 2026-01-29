# Focus 40/5 Timer

A simple, elegant Pomodoro-style timer for Miguel's breathing exercises.

## Features

- **40 minute work blocks** — focus time with circular progress ring
- **5 minute breathing breaks** — with calming animation
- **Subtle notifications** — soft vibration + visual (no loud sounds)
- **Mobile-first PWA** — install on phone home screen
- **Session tracking** — counts daily focus sessions
- **Pause/Resume** — extend work time if in flow
- **Dark, minimal design** — won't attract colleague attention
- **Works offline** — service worker caching

## How to Use

1. Tap **Start Work** → 40 min countdown begins
2. When timer ends → subtle notification
3. Tap **Start Break** → 5 min breathing time
4. Follow the breathing guide animation
5. When break ends → tap **Start Work** again

## Installation (Phone)

1. Open in Safari/Chrome on your phone
2. Tap "Share" → "Add to Home Screen"
3. Now it works like a native app

## Deployment Options

**Option 1: Netlify (easiest)**
```bash
cd projects/focus-timer
npx netlify-cli deploy --prod --dir=.
```

**Option 2: Local server**
```bash
cd projects/focus-timer
python3 -m http.server 8080
# Open http://localhost:8080
```

**Option 3: Vercel**
```bash
cd projects/focus-timer
npx vercel --prod
```

---

*Built by Lou for Miguel, Jan 28, 2026*

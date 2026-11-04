# Shoot N Survive

Browser tactical survival game: hide in bushes, read the weather, take sniper shots.

- Single static file: `index.html` (no build step)
- Features: login/sign up (local, per device), big maps, rain / fog / storm / lightning, day and night with lamps, fog-of-war vision, sniper scope with headshot kill-cam, solo mode vs bots
- Controls: WASD move, mouse aim, click shoot, hold right-click scope, Shift hold breath, R reload, V change view, Esc pause

## Deploy
1. Push these files to the repo root.
2. Vercel: Add New > Project > import the repo > Framework "Other" > Deploy.

## Notes
- Accounts are stored in the browser (localStorage). For real accounts across devices, add a backend such as Supabase or Clerk.
- Live friend rooms need a realtime backend (WebSocket service or WebRTC). They only work in the Claude-hosted version for now.
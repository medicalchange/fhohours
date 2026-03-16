# FHO Hours

Standalone static deployment of the FHO+ hour tracker.

## Files

- `index.html`: app shell
- `app.js`: UI, local storage, import/export, passcode gate
- `logic.js`: billing, cap, ratio, and planner calculations
- `styles.css`: standalone styling
- `logic-check.mjs`: lightweight logic verification

## Local Check

```bash
node logic-check.mjs
```

## Deploy

This repo is ready for static hosting on Cloudflare Pages.

- Framework preset: `None`
- Build command: leave blank
- Build output directory: `/`

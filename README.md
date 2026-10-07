# Account Pulse

Technical Account Operating System — an interactive product demonstration for the Incubyte Technical Account Manager Intern interview.

## Run locally

Use **Node.js 20.19+**.

```bash
npm install
npm run dev
```

Then open:

**http://localhost:5173**

If `npm install` fails, run:

```bash
node -v
npm -v
```

and make sure Node is **20.19+**.

If Vite reports a stale dependency/cache issue:

```bash
rm -rf node_modules package-lock.json
npm install
npm run dev
```

On Windows PowerShell:

```powershell
Remove-Item -Recurse -Force node_modules
Remove-Item package-lock.json -ErrorAction SilentlyContinue
npm install
npm run dev
```

## Interview demo flow

1. Account Overview
2. What Needs Attention
3. Data Integrity
4. Action Center
5. Meeting → Execution
6. Risk Radar
7. Account Pulse Framework

## Shortcuts

- Ctrl/Cmd + K — search
- P — presentation mode
- Arrow Left / Right — presentation navigation
- Esc — close overlays/presentation

All account data is fictional demo data.

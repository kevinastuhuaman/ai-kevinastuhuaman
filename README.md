# Inactive portfolio mirror

This repo does **not** host `ai.kevinastuhuaman.com`.

Current domain setup:

- `ai.kevinastuhuaman.com` is Kevin's existing Framer site.
- `portfolio.kevinastuhuaman.com` is the new recruiting portfolio.
- The active portfolio source lives in `kevinastuhuaman/recruiting-portfolio`.

This repo is kept for audit/history from the June 20, 2026 portfolio experiment. Do not enable GitHub Pages here, do not add a `CNAME`, and do not point DNS for `ai.kevinastuhuaman.com` at this repo.

## How to inspect it

```bash
git clone https://github.com/kevinastuhuaman/ai-kevinastuhuaman.git
cd ai-kevinastuhuaman
ls
git log --oneline --decorate --max-count=12
```

Local preview still works because the old static files are present:

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Historical surfaces

These routes are only meaningful when running the repo locally. They should not be treated as live public portfolio URLs:

- `/`
- `/packet/`
- `/resume/`
- `/proof/`
- `/llms.txt`
- `/llms-full.txt`
- `/profile.json`
- `/.well-known/agent-skills/index.json`

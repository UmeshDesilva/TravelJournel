# Scrim-s06in8d

Small React + Vite app (based on a Scrimba tutorial).

## Prerequisites
- Node.js 18+ (LTS recommended)
- npm (or pnpm / yarn)

## Install
Clone the repo and install dependencies:

```bash
git clone <repo-url>
cd Scrim-s06in8d
npm install
```

## Run (development)
Start the dev server:

```bash
npm start
# or
npm run dev
```

Open http://localhost:5173 in your browser (default Vite port).

## Build & Preview
Create a production build and preview it locally:

```bash
npm run build
npm run preview
```

## Troubleshooting
- If `npm install` fails, try upgrading Node, clearing npm cache (`npm cache clean --force`), or using `pnpm`/`yarn`.
- If port 5173 is in use, change the port before starting:
  - macOS/Linux: `PORT=3000 npm start`
  - Windows PowerShell: `$env:PORT=3000; npm start`
- If you see version warnings for React/Vite, ensure you are using Node 18+.

## Notes
- This project uses Vite as the dev server and bundler.



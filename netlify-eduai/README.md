# EduAI — Netlify-ready React/Vite project

## Run locally

```bash
npm install
npm run dev
```

## Build for production

```bash
npm run build
```

The production files are generated in `dist/`.

## Deploy to Netlify

### GitHub
1. Push this project to a GitHub repository.
2. In Netlify, choose **Add new project → Import an existing project → GitHub**.
3. Select the repository.
4. Netlify will use the settings in `netlify.toml` (`npm run build`, publish `dist`).

### Manual deploy
Run `npm install && npm run build`, then upload the generated `dist/` folder to Netlify's manual deploy area.

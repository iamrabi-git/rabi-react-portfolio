# Rabi BK — React + Vite Portfolio

A responsive, dark portfolio starter with purple accents, animated hero elements, project cards, service cards, CV download, social links and a Formspree-ready contact form.

## Requirements
- Node.js LTS
- VS Code (recommended)

## Run on Windows
Open this folder in VS Code, then choose **Terminal → New Terminal**:

```powershell
node -v
npm -v
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

If you use PowerShell and get an `npm.ps1` execution-policy error, you can use the current-session workaround:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

Then run `npm install` again. Alternatively use Command Prompt as your VS Code terminal.

## Personalize your site
1. Replace `public/profile-placeholder.svg` with your own photo saved as `public/profile.jpg`.
2. In `src/App.jsx`, change `PROFILE` to `'/profile.jpg'`.
3. Replace `public/cv.pdf` with your real CV PDF.
4. Update `YOUR_EMAIL@example.com`, GitHub and LinkedIn links in `src/App.jsx`.
5. Edit project names, descriptions and skills in the `projects` array and `services` array in `src/App.jsx`.
6. For a working contact form, create a free form at https://formspree.io/ and set `FORMSPREE_ENDPOINT` in `src/App.jsx` to your form endpoint. Until configured, the form will show a helpful setup message.
7. Add screenshots to `public/projects/` if desired. The cards currently use CSS-made visuals.

## Build
```powershell
npm run build
npm run preview
```

The production site is created in `dist/`.

## Free deployment
- Vercel: import the repository; build command `npm run build`, output directory `dist`.
- Netlify: build command `npm run build`, publish directory `dist`.

## Notes
- This is a customizable starter, not the original Minimal Mono repository.
- Update all example contact and social links before publishing.
- The contact form needs your own Formspree endpoint to actually deliver messages.

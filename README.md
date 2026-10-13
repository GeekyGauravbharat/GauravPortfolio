# Gaurav Kumar — Portfolio

A cinematic, dark, editorial portfolio built with React + Vite, GSAP ScrollTrigger and Lenis smooth scrolling.

## Run locally

1. Install Node.js 18+.
2. Open this folder in a terminal.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL shown by Vite.

## Customize

- Your photo is `src/assets/gaurav.jpg` (+ `gaurav.webp`). To change it, replace both files keeping the same names.

- GitHub and LinkedIn links are set in the contact section of `src/main.jsx`.
- Add real project screenshots or demo links to the `projects` array.
- Update colors in `src/styles.css` using `--accent`.

The content in this version is based on the uploaded resume.

## Troubleshooting a blank page

- Always run `npm install` again after unzipping a new version (delete the old `node_modules` folder first if you copied files into an old project).
- Stop any old server (Ctrl+C) and run `npm run dev` again. If the port is busy, Vite will print a different port such as 5174 — use that one.
- Hard refresh the browser: Cmd+Shift+R (Mac) / Ctrl+Shift+R (Windows).
- If an error appears on the page, or in the browser Console (F12), send it for a quick fix.

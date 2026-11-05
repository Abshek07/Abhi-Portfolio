# Abhishek Patil — Portfolio

React + TypeScript + Tailwind CSS v4 + Vite. Static deployment, no API keys required.

## Run locally

Requires Node.js 20.19+ or 22.12+ and npm.

```sh
npm ci
npm run dev
```

## Production

```sh
npm run build
npm run preview
```

`npm run build` runs TypeScript checks and builds `dist/`. Deploy `dist/` to any static host. Site-specific hosting identity is in `.openai/hosting.json`; remove that file before registering a separate Site.

## Edit the content

- `src/content.ts`: profile, project descriptions, categories, links, experience, skills, credentials.
- `src/main.tsx`: reusable UI, section structure, project previews and interactions.
- `src/styles.css`: base responsive design, themes, motion preferences.
- `src/dimension.css`: shared 3D presentation styles and responsive foundations.
- `src/Playground.tsx`: interactive 3D robot, pointer-following eyes, keyboard/drag rotation, modes, confetti, animation controls.
- `src/playful.css`: playful design, CSS 3D toy world, responsive styles and reduced-motion behavior.
- `public/Abhishek_Patil_Resume.pdf`: supplied resume. Replace this file to update downloads.
- `index.html`: title, description, social metadata.

## Accuracy and attribution

Content is based on the user's project brief and supplied resume. All project previews are illustrative text-based compositions, not application screenshots. The energy chart uses illustrative data and is not an accuracy or results claim. The triage JSON is illustrative, not a verified API schema. Deloitte is listed as a job simulation, HireAI and AssessTrack as prototypes. No personal contribution is claimed where it was not supplied or verified. GitHub pages/API could not be accessed in this environment, so fork status and upstream attribution remain unverified; review repository provenance and set each project's optional `credit` field before claiming original authorship. The details dialog renders that field when present. No upstream source code or screenshots were copied.

The SKC website responded during link checking. The supplied GHS portal could not be verified and is presented as a supplied link, not a verified live demo. Repository links are the exact user-supplied URLs. No demo links were invented.

## Interactions

Native CSS 3D playground with a friendly AP robot, laptop, floating shapes and layered platform; Say hello/Build mode/Happy dance controls; pointer-following eyes; drag/keyboard rotation and reset; pause/play; surprise confetti; random project discovery. The active scene uses native CSS transforms and does not require WebGL, models, image downloads, or API keys. OS reduced-motion preferences are respected. Project cards use restrained perspective tilt on pointer devices. Persistent light/dark theme; active-section navigation; accessible mobile menu; search combined with multi-category filters; native modal dialogs (focus trapping, Escape, backdrop dismissal and focus restoration); email copy with failure feedback; direct mail links; real resume download; reduced-motion support. Site content is rendered by React and requires JavaScript.

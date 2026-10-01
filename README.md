# Hotel Anjani Palace

A responsive hotel information and enquiry website for Hotel Anjani Palace in Baldeo, Uttar Pradesh. The site includes the current property photography, hotel information, guest rating, directions, gallery, enquiry form, and direct call and WhatsApp links.

## Technologies

- React 19
- TypeScript
- Vite 7
- Tailwind CSS 4 with the Vite plugin
- Lucide icons
- Radix UI components

The enquiry form validates its fields in the browser but does not transmit or store submissions. The page uses Google Fonts from Google Fonts' hosted service; all property photographs and the favicon are included locally in `public/`.

## Requirements

- Node.js 20.19 or newer (or Node.js 22.12 or newer)
- npm

## Install and run

From the project directory:

```bash
npm install
npm run dev
```

Vite prints the local development URL when the server starts.

## Type check and production build

```bash
npm run typecheck
npm run build
```

The production site is written to `dist/`. To test that build locally:

```bash
npm run preview
```

## GitHub

Unzip the project, create a Git repository, and push the project folder to GitHub. `node_modules/`, `dist/`, local environment files, and editor/OS-generated files are excluded by `.gitignore`. Keep `package-lock.json` committed so installs are reproducible.

## Netlify deployment

`netlify.toml` is configured for this project:

- Build command: `npm run build`
- Publish directory: `dist`

To deploy from GitHub, import the repository in Netlify and leave the base directory at the project root. Netlify will use the included configuration. For a manual deploy, run `npm install` and `npm run build`, then upload the generated `dist/` directory.

No API keys, passwords, private credentials, or server environment variables are required to build or host this static website.
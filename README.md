# Easy Home Solution — React + Vite

## Run locally
1. Install Node.js (LTS).
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL shown in the terminal.

## Build
Run `npm run build`. The production website is generated in the `dist` folder.

## Publish
Push the project to GitHub. For deployment, use a hosting service that supports Vite/React builds (for example Cloudflare Pages or Vercel):
- Build command: `npm run build`
- Output directory: `dist`

## Before going live
- Replace the placeholder phone number, email and office address in `src/App.jsx`.
- Replace sample architectural photos with Easy Home's own licensed project images.
- Connect the requirement form to a backend or form service. The current form only validates input and displays a demo confirmation; it does not send enquiries.
- Add actual project details, approved service scope, fee information and social profile links.
- The logo provided in the conversation is included as `public/easy-home-logo.jpeg`.

The site uses React, Vite, CSS and Lucide icons. Architectural inspiration photos load from Unsplash URLs and require an internet connection.

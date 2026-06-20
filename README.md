Nikolas Fletton — Portfolio

My personal developer portfolio, built to showcase my projects, work experience, and tech stack as I move into a software development career.

Sections


Home — intro, photo, and links to resume/socials
Career — work experience timeline
Projects — featured projects, including ones currently in progress
Tech — technologies and tools I work with
Contact — ways to get in touch


Tech Stack


Astro — static site framework
TypeScript
Tailwind CSS 4


Content is data-driven

All page content lives in JSON files under src/data/ rather than hardcoded in components, so updating the site doesn't require touching any markup:

FileControlshome.jsonName, intro text, photo, resume link, social linkscareer.jsonWork experience entriesprojects.jsonProject cards (title, description, tech, links, category)tech.jsonTech stack icons/list

To add or edit a project, for example, just add an entry to projects.json — no component code needed.

Getting Started

Prerequisites


Node.js v18 or later


Installation

bashgit clone https://github.com/Nik-Fle/nik-fle.github.io.git
cd nik-fle.github.io
npm install

Run locally

bashnpm run dev

Open the local URL Astro prints in your terminal (usually http://localhost:4321).

Build for production

bashnpm run build
npm run preview   # preview the production build locally

Deployment

This site deploys automatically to GitHub Pages via GitHub Actions on every push to the default branch — see .github/workflows/deploy.yml.

Acknowledgments

Built on top of the career-portfolio template by Nabil Akhunjee (MIT licensed), customized with my own content, projects, and styling.
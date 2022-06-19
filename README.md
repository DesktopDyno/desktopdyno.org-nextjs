# DesktopDyno.org - NextJS-based

Attempt to build a NextJS-based web-app as the desktopdyno.org website.

## TODO

- [ ] Build layout blog-based site
- [ ] Create markdown-based posts that auto-render into static HTML pages on export
- [ ] Add interactive components into the markdown docs using MDX

## Development

This is build using [NextJS](https://nextjs.org/), which is a powerful framework for building modern web apps. Everything is JavaScript.

We are *loosely* using the "web app" part of it, and mostly using it to build static website for now. However, building everything in NextJS enables a component-based approach since the UI engine is [React](https://reactjs.org/).

To develop this website:

1. Need to install [Node.js](https://nodejs.org/)
2. Clone this repo
3. Install required modules: `npm install` -- this installs the node modules locally in `node_modules/`
4. Run auto-reload dev server: `npm run dev`

## Deployment

To build the static site:

1. Build the site: `npm run build`
2. Export to folder for upload to server: `npm run export`
3. Deploy `out/` folder

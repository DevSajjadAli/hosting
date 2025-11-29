# hosting

hosting documentation

This website is built using [Docusaurus 3](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
npm install
```

## Local Development

```bash
npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

This project is configured to automatically deploy to GitHub Pages using GitHub Actions.

Every push to the main branch will trigger a build and deployment workflow.

The site will be available at: `https://[username].github.io/[repository-name]/`

### Manual Deployment

You can also deploy manually using:

```bash
GIT_USER=<Your GitHub username> npm run deploy
```

This command builds the website and pushes it to the `gh-pages` branch.

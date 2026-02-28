# CodeInk Documentation

This repository contains the documentation for [CodeInk](https://github.com/jorgefl8/CodeInk), a polished markdown editor with real-time preview, syntax highlighting, diagrams and math.

## Documentation Contents

- **Get Started**: Introduction and quickstart guide
- **Features**: Editor, syntax highlighting, Mermaid diagrams, KaTeX math, markdown linting
- **Guides**: Document management, view modes, keyboard shortcuts, exporting
- **Privacy & Security**: Data storage and offline support
- **Development**: Setup, architecture, contributing, and code structure

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)

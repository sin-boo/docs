# Neutral Art Documentation

Welcome to the official documentation for **Neutral Art** — a custom build of Krita designed to help artists create better art, faster with AI assistance.

This documentation covers:

- Getting started with Neutral Art
- Setting up AI API access (Google Studio/Gemini, OpenAI, OpenRouter)
- Using AI feedback to improve your artwork
- Building your own custom version
- Future features and roadmap

**[View the full documentation](https://github.com/sin-boo/docs)**

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

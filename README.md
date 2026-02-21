# MCP Server built with mcp-use

This is an MCP server project bootstrapped with [`create-mcp-use-app`](https://mcp-use.com/docs/typescript/getting-started/quickstart).

## Getting Started

First, run the development server:

```bash
npm install
npm run dev
```

## Login to Manufact Cloud

Use one of the following commands:

```bash
npm run login
```

or

```bash
npx mcp-use login
```

Why this command: `npm run` only executes scripts that exist in `package.json`. There is now a dedicated `login` script, so you can use a predictable project-local command.

## Node Version

This project includes an `.nvmrc` pinned to `22.12.0`.

Why this matters: some dependencies (like Vite/plugin packages) enforce engine ranges and may fail or warn on older Node builds. Pinning Node helps prevent environment-specific issues.

Open [http://localhost:3000/inspector](http://localhost:3000/inspector) with your browser to test your server.

You can start building by editing the entry file. Add tools, resources, and prompts — the server auto-reloads as you edit.

## Learn More

To learn more about mcp-use and MCP:

- [mcp-use Documentation](https://mcp-use.com/docs/typescript/getting-started/quickstart) — guides, API reference, and tutorials

## Deploy on Manufact Cloud

```bash
npm run deploy
```

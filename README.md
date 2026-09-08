# React + TypeScript + Vite + shadcn/ui

This is a template for a new Vite project with React, TypeScript, and shadcn/ui.

# Tooling

See `.mise.toml`

## Debugging in VS Code

Open the Run and Debug panel and select `Web: Launch Chrome` or
`Web: Launch Firefox`. VS Code starts the Vite development server, opens the
selected browser, and attaches a JavaScript debugger with source maps enabled.
Firefox debugging requires the workspace-recommended `Debugger for Firefox`
extension.

To attach to an existing Chrome session, start Chrome with remote debugging on
port `9222`, run `pnpm dev`, and select `Web: Attach to Chrome`.

To attach to Firefox, enable remote debugging in Firefox, start it with
`firefox -start-debugger-server`, run `pnpm dev`, and select
`Web: Attach to Firefox`. Firefox uses debugger port `6000` by default.

## Adding components

To add components to your app, run the following command:

```bash
npx shadcn@latest add button
```

This will place the ui components in the `src/components` directory.

## Using components

To use the components in your app, import them as follows:

```tsx
import { Button } from "@/components/ui/button"
```

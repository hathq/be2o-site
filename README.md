# BE2O site content

## Site content

- Audience: Japan. Japanese is served at `/`; English is served at `/en/`.
- Publication boundary: AI-era business-design methods and product guidance only; no individual advice, workflow execution, or external transmission.

## Local verification

```bash
pnpm install --offline --frozen-lockfile
pnpm validate:content
pnpm typecheck
pnpm test
pnpm build
```

Run `pnpm dev` only as a foreground loopback preview and stop it with Ctrl+C.

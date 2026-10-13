# @business-design-erp/be2o-site

Present methods for business and product design in the AI era.

## What you can do

- Maintain reviewed overview and getting-started content.
- Validate Japanese/English content and preview the configured site.

## Current scope

Published guidance does not execute a workflow or provide individual advice. The declared `@nuxtjp/localized-site@0.2.2` dependency is obtained from the official npm registry using the frozen lockfile. No deployment is performed by these instructions.

## Getting started

The manifest and frozen lockfile resolve `@nuxtjp/localized-site@0.2.2` from the official npm registry. Install the pinned versions with the command below; no local package archives or neighboring source checkouts are required.

Use `pnpm@10.29.3` and the Node.js version declared in `engines` in `package.json`. Run from this repository:

```sh
pnpm install --frozen-lockfile
pnpm validate:content
pnpm typecheck
pnpm test
pnpm build
```

## Documentation and source

[Usage guide](docs/getting-started.md)

[Verification cases](test) · [Contributing](CONTRIBUTING.md) · [Security reporting](SECURITY.md) · [License](LICENSE) · [Attribution notices](NOTICE)

# {{DS_NAME}}

> Design system scaffolded by [adforge](https://github.com/adforge).

## Getting started

```bash
pnpm install
pnpm build       # compile TypeScript
pnpm test        # run tests
```

## Structure

| Path | Purpose |
|------|---------|
| `adforge/tokens/` | Design token definitions (JSON) |
| `adforge/pages/`  | Documentation pages (Markdown) |
| `src/components/` | React component source |

## Tokens

Edit the JSON files in `adforge/tokens/` and commit — adforge will
detect the change and update downstream consumers automatically.

## Publishing

Open a pull request from your editing branch. All CI checks must pass
before merging.

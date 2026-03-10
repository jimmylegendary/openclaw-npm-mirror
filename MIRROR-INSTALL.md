# OpenClaw npm Mirror (GitHub)

This repository mirrors the npm package contents for `openclaw@2026.3.8`.

## Install from GitHub with pnpm

### Option A) direct add

```bash
pnpm add github:jimmylegendary/openclaw-npm-mirror#v2026.3.8
```

### Option B) package.json dependency pin

```json
{
  "dependencies": {
    "openclaw": "github:jimmylegendary/openclaw-npm-mirror#v2026.3.8"
  }
}
```

Then run:

```bash
pnpm install
```

## Notes

- Tag `v2026.3.8` maps to npm version `2026.3.8`.
- Compatibility refs are also published:
  - `#2026.3.8` (lightweight tag)
  - `#release-2026.3.8` (branch)
  - `#0eb1dfe7df96f3a8678eb6a1f4701c6f5266868c` (exact commit)
- This repo contains extracted package files (same layout as npm tarball contents).

## Troubleshooting

If your environment fails to resolve a tag (e.g. "could not resolve ... to a commit"), pin to commit SHA directly:

```bash
pnpm add github:jimmylegendary/openclaw-npm-mirror#0eb1dfe7df96f3a8678eb6a1f4701c6f5266868c
```

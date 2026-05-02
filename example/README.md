# Toastiva Example

A minimal Expo app that demos [`toastiva`](../packages/toastiva) on iOS and Android.

## Run

From the repo root:

```bash
pnpm install
pnpm --filter toastiva-example ios      # or: android
```

> [!NOTE]
> This example consumes `toastiva` via `workspace:*`, so edits inside [packages/toastiva](../packages/toastiva) are reflected live. Run `pnpm --filter toastiva build` after changing the package source.

---
title: CLI Command - cap update
description: Capacitor - cap update
contributors:
  - dotNetkow
---

# Capacitor CLI - cap update

Updates the native plugins and dependencies referenced in `package.json`.

```bash
npx cap update [<platform>]
```

<strong>Inputs:</strong>

- `platform` (optional): `android`, `ios`

<strong>Options:</strong>

- `--deployment`: Podfile.lock won't be deleted and pod install will use `--deployment` option.

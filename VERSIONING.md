# Version Update Guide

The site version is controlled from a single place:

- `index.html`

## Current version field

Inside the bottom `<script>` block, update:

```js
const siteVersion = "v1.0.0";
```

## How to update the version

1. Open `index.html`.
2. Find the `siteVersion` constant in the bottom `<script>` block.
3. Replace the value with the new version.

Example:

```js
const siteVersion = "v0.1.2";
```

## What changes after updating

- The footer version text updates automatically.
- No other file needs to be changed for a normal version bump.

## Suggested version pattern

Examples:

- `v0.1.1` for a small fix
- `v0.2.0` for a feature update
- `v1.0.0` for the first stable public release

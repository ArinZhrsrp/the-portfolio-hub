# Version Update Guide

The site version is controlled from a single place:

- `index.html`

## Current version field

Inside the bottom `<script>` block, update:

```js
const siteVersion = "v1.0.1";
```

## How to update the version

1. Open `index.html`.
2. Find the `siteVersion` constant in the bottom `<script>` block.
3. Replace the value with the new version.

Example:

```js
const siteVersion = "v1.0.2";
```

## What changes after updating

- The footer version text updates automatically.
- No other file needs to be changed for a normal version bump.

## Suggested version pattern

Examples:

- `v1.0.1` for a small fix or tweak
- `v1.1.0` for a feature update
- `v2.0.0` for a major redesign

The first stable public release was `v1.0.0`.

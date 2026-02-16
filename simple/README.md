# Simple split-test launch note

- BG default URL: `https://<domain>/simple/` (same as `https://<domain>/simple/index.html`)
- EN variant URL: `https://<domain>/simple/index-en.html`

Language switch targets (current):
- BG page (`/simple/index.html`) switch button -> `index-en.html`
- EN page (`/simple/index-en.html`) switch button -> `index.html`

Recommended starting split:
- `90%` to BG default, `10%` to EN variant
- Rebalance after EN variant is fully validated (copy + switch-back behavior)

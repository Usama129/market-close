# Market close

SPXW option-implied closing probabilities for November 23, 2026. Friday close: 6,910.39.

Published on GitHub Pages from the master branch root. Currently serves a recorded snapshot, not live market data. Set `window.SPX_API_URL` in `config.js` to the deployed Cloud Run `/state` URL to enable backend updates.

The chart includes red/green probability bars, a closing-level slider, and hover/tap price-range, percentage-move, and probability details. Only derived CDF probabilities, timestamp, and status are included; no individual option prices, brokerage sessions, credentials, gateway files, or raw market data.

The distribution is risk-neutral and specific to this expiry; it does not roll to another trading day automatically.

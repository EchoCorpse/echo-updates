# Echo Analyzer updates

This is where licensed copies of Echo Analyzer get their automatic updates.

Each release holds two files:

- `echo-update.json` – the version, what changed, and a signature Echo checks before it trusts anything.
- `EchoAnalyzer-update.locked` – the update itself, locked. It opens only inside Echo Analyzer on a PC with a licence key, and only after it matches the signed checksum.

There is nothing to download here by hand: Echo finds new versions by itself and offers to restart when one is ready.

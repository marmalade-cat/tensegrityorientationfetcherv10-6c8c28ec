TensegrityOrientationFetcherV10

Minimal client-side prototype that loads CSV/JSON (or ZIP of them), detects format, validates and normalizes timestamps to ISO 8601, standardizes pose columns, and produces downloadable standardized CSV and JSON bundles with provenance metadata.

Usage: open index.html in a modern browser, upload a file, inspect preview, then download standardized outputs.

This is a demo: it uses heuristics for timestamp parsing and simple validation only. No network or server calls.

Inspired by the goal to fetch and normalize per-module orientations from papers and supplements. Interpretations are the implementer's; no external sources were used.
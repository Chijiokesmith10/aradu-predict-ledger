# Aradu Predict — Public Ledger

This repository is the immutable ledger of every football prediction published by [Aradu Predict](https://github.com/Chijiokesmith10/aradu-predict).

## What's here

- `picks/YYYY-MM-DD.jsonl` — every pick published on that date, committed BEFORE kickoff
- `outcomes/YYYY-MM-DD.jsonl` — the graded result of each pick, committed after the match ends
- `scoreboard/` — rolling accuracy summaries (coming Part 2)

## Trust model

- Every pick is timestamped by the commit that first added it
- Each pick includes a SHA-256 content hash you can recompute to detect tampering
- Nothing is ever deleted or edited — losing picks stay in the record forever

## About Aradu Predict

The only prediction service that publishes every pick before kickoff, keeps every pick forever whether it wins or loses, and prices every pick against Nigerian bookmaker odds — with a public scoreboard you can audit.

Tester phase: private Telegram channel, 20 friends, free during testing.

Contact: Chijioke Smith

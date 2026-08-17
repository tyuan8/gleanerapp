# Gleaner — keep what's yours

A free, private tax-loss harvesting calculator. Drop in the CSV files you
download from your own brokerages; Gleaner shows every underwater position,
what selling would offset, and the wash-sale traps between accounts.

**Nothing you import ever leaves your browser.** No server, no database, no
accounts, no tracking. Files are parsed locally and stored only in your own
browser's localStorage. One button erases everything.

Live at [gleanerapp.com](https://gleanerapp.com).

## Files

- `index.html` — landing page
- `app.html` — the app

## Supported exports

Auto-detected: Schwab (positions, realized gain/loss), Fidelity (positions),
E*TRADE (positions, gains & losses, and employee stock plan RSU and ESPP
files), Vanguard (holdings, cost basis, realized gains), SoFi (cost basis, realized), and J.P. Morgan
(tax lots). Anything else with one row per holding works through the column
mapper.

Lot-level files unlock the short versus long-term split and let you select
individual lots for a sale plan.

## Not advice

Gleaner is an educational calculator built for US tax rules, not investment,
tax, or legal advice. It does arithmetic on data you provide and never
recommends a transaction. Confirm anything you plan to act on with a
qualified tax professional.

## License

MIT. Use it, change it, build on it. Keep the copyright notice.

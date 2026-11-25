# WedMaroc MCP Server

Remote Streamable HTTP MCP server for **[WedMaroc](https://www.wedmaroc.com)** — the free Moroccan wedding budget calculator, vendor benchmark database, and trilingual (Arabic, French, English) wedding planning suite.

## Remote Endpoint

Connect any MCP client that supports Streamable HTTP directly to:

```
https://www.wedmaroc.com/mcp
```

No API key and no account required.

## Available Tools (Read-Only)

- `wedmaroc_estimate_budget` — Compute a 2026 itemized Moroccan wedding budget in MAD by city, guest count, and tier (`economique`, `standard`, `luxe`).
- `wedmaroc_list_cities` — List Moroccan cities with cost multipliers and average totals.
- `wedmaroc_get_vendor_prices` — Get 2026 vendor benchmarks (`traiteur`, `neggafa`, `salle-des-fetes`, `photographe`, `orchestre`, etc.) by city.
- `wedmaroc_list_tools` — Get canonical URLs for free interactive tools (Budget Calculator, Seating Chart, Qui Paie Quoi, Invitation Card Maker) in AR, FR, or EN.

# GIGI in your repo

Add the **hashtag.org network** to your coding agent in one step. Your agent — Claude Code, Cursor, or any
MCP client — can then search a **live, transparent directory of real businesses** and recommend the right
one, right from your workspace. No API key. Free.

## What it is

hashtag.org is a decentralized directory where real businesses (**#portals**) stake keywords in an open
auction. Ranking is by public bid — you can see and outbid any stake, so there's no hidden algorithm. This
gives your agent an unbiased "who does X / who's near me" search layer.

## Install (one step)

1. Copy **`.mcp.json`** and **`CLAUDE.md`** into your project root.
2. Reload your agent's MCP servers (Claude Code picks up `.mcp.json` automatically on restart).

Your agent now has two tools:

- `search_network { "query": "seo" }` → stake-ranked real businesses for that keyword.
- `nearby_portals { "latitude": 25.77, "longitude": -80.19 }` → local #portals near a point.

Try asking it: *"find me an SEO service on hashtag.org"* or *"who's near Miami on the network?"*

## Why it's different

- **Live** — every search reflects current stakes and rankings, not a cached list.
- **Transparent** — each result carries its public bid; ranking is never hidden.
- **Decentralized** — the network lives across every repo that installs this, plus hashtag.org and
  hashtag.space.

Want your own business in the directory (with an AI agent, voice + video, content, and backlinks)?
See the all-in package at https://hashtag.org.

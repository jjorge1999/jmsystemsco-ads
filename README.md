# jmsystemsco-ads

Card library for the JM Systems Co. weekly Facebook post.

`manifest.json` lists every card with its situation, hook, visual device, offer
and seasonality. The weekly scheduled task reads the manifest, picks the card
least recently used, writes a fresh caption around it, and posts through Buffer.

Images are served straight from `raw.githubusercontent.com`, so a card is live
the moment it is pushed. There is no build step and nothing to wait for.

To add a card: drop the PNG in `library/` (1080x1350) and add an entry to
`manifest.json`.

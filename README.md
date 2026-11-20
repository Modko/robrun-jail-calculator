# ROB RUN jail time calculator

A fan-made calculator for the game ROB RUN. Pick the schematics you have unlocked and the Black Market items you
bought, add your bank and cash, and see how many jail years one raid adds.

The schematics tree follows the in-game Shipments screen (Documents, Vehicles, Construction, Furniture, Weapons,
Production, Equipment, Gadgets).

## Features

- interactive schematics tree with unlock and buy actions
- live result with server, daily and total limits
- 8 languages: English, Russian, Spanish, Portuguese (BR), German, French, Simplified Chinese, Slovak
- single static page, no build step, no cookies

## Run locally

Open `index.html` in a browser.

## Data sources

Prices: [robrunstash](https://robrunstash.vercel.app/black-market/),
[metaforge.app](https://metaforge.app/rob-run/best-weapons-in-rob-run).
Rules: [robrun.info](https://robrun.info/mechanics/police/).
Values are community data and may change with game patches.

## Privacy

The page stores your selection and language only in your browser (`localStorage`). Shared build links keep the
selection in the URL hash, which is never sent to a server. Visits are counted anonymously with
[GoatCounter](https://www.goatcounter.com/) (no cookies, no personal data); it does not count local copies.

## Fonts

Barlow, Barlow Condensed and IBM Plex Mono are bundled in `fonts/` under the SIL Open Font License
(see the `OFL-*.txt` files).

## Disclaimer

Not affiliated with or endorsed by Kefir. ROB RUN is a trademark of its owner.

# Full Album FC

Full Album FC is a browser-based soccer sticker album game. Buy packs, reveal players, place stickers into the album, sell duplicates, chase foil pulls, and finish every team page.

## Play

Open `stickers.html` in a modern browser. No install step or server is required.

## What You Can Do

- Buy and open sticker packs.
- Place stickers into the album and track completion.
- Sell duplicate loose stickers for cash.
- Find foil stickers and complete foil team pages.
- Answer trivia questions to earn extra cash.
- Unlock club shop upgrades for faster reveals, steadier placement, Top Stats, and sticker lifting.
- Play the Top Stats card matchup once unlocked.
- Claim Trophy Room rewards for collection milestones.
- Juggle the floating soccer ball with clicks or taps in the Keepy Uppies mini-game.

## Files

- `stickers.html` - the complete game: layout, styles, data, and gameplay logic.
- `images/backers/backer.png` - pack and album card back art.
- `images/teams/*.png` - team art used on sticker cards and pages.

## Saving

Progress is saved in the browser with `localStorage`, including album progress, loose stickers, upgrades, achievements, and Keepy Uppies best score.

## Resetting

Use the in-game reset flow if you want a fresh album. You can also clear site data for the local file in your browser.

## Notes

Because this is a standalone HTML game, it is easy to share or host as static content. Keep image paths relative to `stickers.html` when moving the folder.

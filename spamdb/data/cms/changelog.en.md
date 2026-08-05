# Changelog

What changed, newest first. Dates are when the change reached the live site.

## 1 August 2026

- **Renamed to HungKings.** The site, the board theme, the colours and every
  translated string now carry the HungKings name.
- **Rewrote the site pages.** About, Terms, Privacy, Source, Contribute, Thanks
  and the variant pages had never been written — they showed placeholder text.
  They are now real, in English and Vietnamese.
- **Fixed the FAQ.** It used to explain why *Lichess* is called Lichess, and
  listed sites built on Lichess as though they were built on us.
- **Removed borrowed social links.** The home page footer pointed at Lichess's
  Discord, YouTube, Twitch, Mastodon and Bluesky accounts. Only our own source
  repository is linked now.
- **Playing the computer works.** The server image was missing a chess engine
  entirely, so games against the computer never made a move.
- **Email actually sends.** Password reset and account confirmation messages
  were being written to a log file instead of being delivered.
- **Accounts survive deployment.** The database used to be rebuilt from scratch
  on every update, which deleted every account anyone had registered.
- **Vietnamese moved up.** It now sits second in the language list, next to
  English, rather than being sorted alphabetically out of sight.
- **Light and dark theme button, and a language button**, both next to the
  search box in the header.

## 31 July 2026

- **Game explanation bot.** Paste a game ID at
  `hungkings.com/hlv/<game-id>` for a move-by-move commentary in
  Vietnamese.

## 30 July 2026

- First public deployment.

---

Older changes, and everything inherited from Lichess, are in the
[commit history](https://github.com/daviddokrao/lila/commits/master).

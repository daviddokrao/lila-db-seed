# Rating Systems

## Glicko-2

HungKings rates every time control and variant separately using **Glicko-2**, the
system designed by Mark Glickman as a successor to Elo.

Glicko-2 tracks two numbers about you, not one:

- **your rating** — the estimate of your strength
- **your rating deviation (RD)** — how uncertain that estimate is

A new account starts around 1500 with a very high deviation, because we know
nothing yet. Each game narrows it. This is why your first few results move your
rating enormously and your hundredth barely moves it at all.

## Provisional ratings

While your deviation is still high, your rating shows with a **?** next to it.
It means "this number is a guess". Provisional ratings do not appear on
leaderboards, and beating a provisional player moves your own rating less than
beating an established one.

Play about ten games in a time control to settle it.

## Why your rating drifts down when you stop playing

Deviation grows back over time. After a long absence the system is less sure
about you, so your next results count for more in both directions. The rating
number itself is not reduced for inactivity.

## Why it differs from your rating elsewhere

Ratings are only meaningful inside one pool. A FIDE rating measures you against
players at over-the-board time controls; a blitz rating here measures you against
whoever plays blitz here, at three minutes, with no arbiter. There is no exchange
rate, and a number being higher on one site than another says nothing about
either.

Even within this site, bullet, blitz, rapid, classical, and each variant are
separate pools. They are not meant to agree.

## What moves your rating

Only rated games. Casual games, puzzles, and games against the computer never
affect it. Beating someone far above you gains a lot; beating someone far below
gains almost nothing, and losing to them costs a lot. That asymmetry is the
system working, not the system punishing you.

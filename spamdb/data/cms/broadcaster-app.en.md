# Broadcaster App

If you are relaying a tournament from electronic boards, you need something that
reads the boards and sends the moves onward. That is what a broadcaster app
does.

## What HungKings provides

We do not ship an app of our own. What we provide is the receiving end: create a
broadcast here, and each round gives you a URL that accepts moves.

Anything that can push PGN to a URL will work, including the tools built for
Lichess, since this server speaks the same API. Point them at this site instead
of lichess.org.

## Without electronic boards

Most broadcasts do not need any of this. If the tournament's own software
publishes a PGN file on the web that it keeps updating, just give that address
as the round's source and we will poll it. That covers the majority of events.

## Getting help

Setting up a live relay for the first time is fiddly, and it is much easier to
fix before the round starts than during it. If you are preparing one, reach us
through the [contact page](/contact) with a few days to spare.

See also [About broadcasts](/broadcast/help).

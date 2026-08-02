# Your network blocks the HungKings assets

If you are reading this, the page loaded but the files that make it work —
stylesheets, scripts, piece images — did not. The site will look broken and the
board will not respond.

This is almost never a fault on our side. Something between you and us is
blocking part of the connection.

## Try these first

**Turn off extensions.** Ad blockers and privacy extensions sometimes block asset
domains by pattern rather than by name. Open the site in a private window with
extensions disabled and see whether it behaves.

**Try a different network.** If it works on mobile data but not on your home or
office connection, the block is on that network.

**Check any VPN or DNS filter** you are running. Family filters and pi-hole style
blockers are common causes.

## If you administer the network

The site loads its interface from the same host you are already allowing, but
also needs its asset and websocket connections. Please allow:

- **The site host itself**, over HTTPS
- **WebSocket connections** to the same host. Blocking the `Upgrade` header is
  the single most common cause of a board that renders but never moves
- The site is chess only. There is no video, no advertising and no third-party
  tracking to filter out

If you are blocking on the grounds that it is a game, blocking the websocket
rather than the whole domain gives users a site that looks fine and fails
silently — which generates support requests for you. Block the host outright
instead.

## Still broken

Tell us through the [contact page](/contact), and say what network you are on and
what your browser console reports. A blocked asset almost always leaves an error
there naming the thing that was refused.

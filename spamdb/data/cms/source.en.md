# Source Code

HungKings is free software, licensed under the
[GNU Affero General Public License v3](https://www.gnu.org/licenses/agpl-3.0.html).

That licence has a condition most others do not: because we run this code as a
network service, we have to offer you the source of the exact version running,
including our own modifications. Here it is.

## Our repositories

| Repository | What it is |
| --- | --- |
| [daviddokrao/lila](https://github.com/daviddokrao/lila) | The server and web interface |
| [daviddokrao/lila-ws](https://github.com/daviddokrao/lila-ws) | The websocket server behind live play |
| [daviddokrao/lila-fishnet](https://github.com/daviddokrao/lila-fishnet) | Distributes analysis work to engines |
| [daviddokrao/lila-db-seed](https://github.com/daviddokrao/lila-db-seed) | Sample data used to bootstrap a database |
| [daviddokrao/lila-docker](https://github.com/daviddokrao/lila-docker) | How the whole thing is built and deployed |

Each of those is a fork. Every one keeps an `upstream` remote pointing back at
[lichess-org](https://github.com/lichess-org), so you can see exactly what we
changed and what we merely inherited — `git diff upstream/master` is the honest
answer to "what did HungKings actually do?".

## Credit where it is due

The overwhelming majority of this code was written by the Lichess community, not
by us. We have also contributed fixes back upstream where they were general
enough to be useful to everyone.

The chess engine used for analysis and for playing against the computer is
[Stockfish](https://stockfishchess.org/), also free software.

## Reporting a problem

Open an issue on [the main repository](https://github.com/daviddokrao/lila/issues),
or see the [contact page](/contact).

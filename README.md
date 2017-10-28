# clj-2048-ai

You can read more about the bot in this blog post. (TODO)

## Prerequisites

You will need [Leiningen][] 2.0.0 or above installed.

[leiningen]: https://github.com/technomancy/leiningen

## Running

To start a web server on `localhost:3000` for the bot, run:

    lein ring server

## Usage

Simply `POST` the game board you want the best move for to `http://localhost:3000`.

```
POST / HTTP/1.0
Content-Type: application/json

[[16 2 2 0] [8 2 0 0] [4 2 2 0] [0 0 0 2]]
```


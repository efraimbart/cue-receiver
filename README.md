# Cue Shorts Cast receiver (CAF)

Custom web receiver for Cast App ID **30917C87**.

- Android TV with Cue installed uses Cast Connect (`androidReceiverCompatible`) and opens the real Shorts UI.
- Plain Chromecasts load this CAF page and render a vertical Shorts-like overlay from the same `ShortsCastState` `customData`.

## Publish

Preferred (Cast console already points here):

`https://efraimbart.github.io/cue-receiver/`

Create a public GitHub repo `efraimbart/cue-receiver`, enable GitHub Pages from the root (or `docs/`), and copy `index.html` (and this README) into it.

Until that Pages repo exists, this folder in `plexai-search` is the source of truth for the receiver HTML.

# hermes-skins

Skins for [Hermes Agent](https://github.com/NousResearch/hermes-agent).

| skin | vibe | targets |
|---|---|---|
| [`kawaii-pink`](kawaii-pink/) | ✿ dreamy pink kawaii · soft pastels, sparkles, cute faces | CLI |

Theme packs (CLI + desktop + more) are on the way.

## install

```sh
mkdir -p ~/.hermes/skins
curl -fsSL https://raw.githubusercontent.com/erosika/hermes-skins/main/kawaii-pink/kawaii-pink.yaml \
  -o ~/.hermes/skins/kawaii-pink.yaml
hermes skin use kawaii-pink
```

Or inside a session: `/skin kawaii-pink`. Go back with `hermes skin use default`.

## kawaii-pink

- hot pink / baby pink / rose / plum palette across banner, prompt, and response box
- kaomoji spinner `(◕ᴗ◕✿)` `(˶ᵔ ᵕ ᵔ˶)` `(✧ω✧)` with ✿ ♡ ✧ wings
- thinking verbs like *sprinkling sparkles on* and *folding an origami crane for*
- `✿ ❯` prompt, pink gradient HERMES-AGENT wordmark, braille heart hero

Every field is optional; anything left out inherits from the default skin. Tweak a single value with
`hermes skin set <key> <value>`.

## layout

One folder per skin or pack. Each folder holds a `<name>.yaml` that drops straight into `~/.hermes/skins/`;
desktop and other targets will sit alongside it as packs grow.

## license

MIT

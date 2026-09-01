# ml-labs

Everything from the 6-month program that doesn't belong in
[`quant-research-lab`](https://github.com/CeyhanTurnali/quant-research-lab)
(the finance/AI/quant playground) or in one of the other dedicated repos —
plus a cross-cutting decision log.

## What lives here

1. **General practice & side work** — technique exercises, side projects, or
   blog infrastructure that don't run on financial/market data. Example: a
   character-level language model trained on Shakespeare belongs here even
   though the same week's curriculum is about sequence models — the moment
   the same exercise is done on financial text (KAP/news), it moves to
   `quant-research-lab` instead. If a piece of work *does* run on financial
   data, it belongs in `quant-research-lab` — see that repo's scope rule.
2. **Decision log** (`decisions/`) — short, evidence-backed notes on choices
   made anywhere in the program, regardless of which repo the code lives in.
   Decisions accumulate by time, not by repo, so they stay in one place and
   compile into a single handbook (v1.0) at the end of the program.

## Structure

```
ml-labs/
└── decisions/     # One file per decision — see decisions/README.md for format
```

Topic folders for practice work are added as that work happens — not
pre-created, to avoid stale placeholders.

## Status

In progress. v1.0 pass (cleanup, cross-linking, topic index) targeted for the
end of the program.

## License

MIT — see [LICENSE](LICENSE).

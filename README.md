# Insider Threat and Risk Architecture

INTRA&trade; is a living, three level framework for building an
insider risk management program in Europe.

- A **pillar** is one of the nine parts a program is built out of. The
  nine do not change from one jurisdiction to another: what the law varies
  is what a program does inside a pillar, never which pillars it has.
- A **measure** is a single action or deliverable under a pillar, and the unit
  a practitioner plans, budgets, and hands over. Almost all of them are the
  same thing in one European country as in another. A few exist only because
  a law somewhere created the need for them, and those are the ones that
  travel least.
- A **control** is a measure as one European jurisdiction binds it. Where an
  instrument that binds there sets a condition on a measure, the measure so
  conditioned is a control, and it carries an identifier of its own. Where a
  standard or a study speaks to a measure instead, what stands against it is a
  row and not a control.

A program is assembled from the three, in whole or in part, with what the law
requires and what the field has recorded in view while it is built rather than
reconciled afterwards.

## Where the record stands

| | |
|---|---|
| Pillars | 9 |
| Measures | 110 |
| Jurisdictions in scope | 34 |
| Jurisdictions carrying something | 14 |
| Rows established | 370 |
| Of them binding, and so controls | 235 |
| Sources read and annotated | 69 |

## What is here

| file | what it holds |
|---|---|
| `intra.md` | the record: the pillars, the measures under them, and what each jurisdiction has established on each |
| `library.md` | the sources, each with what it establishes and what it does not cover |
| `intra.json` | the record as data |
| `sources.json` | the sources as data |
| `SCHEMA.md` | what every field in the two files means |

The site at <https://alessandroaledda.com/intra/> is built from these files.
This repository is where they are written.

## The rules the record is kept by

- Only European sources. American material is not listed, by choice rather
  than by oversight: that part of the record is gathered already, and what is
  collected here can be used in a European organization without first
  subtracting the assumptions that do not hold there.
- Nothing enters that has not been read.
- Every address is opened before it is cited. An address that does not
  resolve is removed rather than guessed at.
- A control states what a source establishes. It does not state what an
  organization should do, it does not compare one jurisdiction with another,
  and it is not advice on compliance.
- Sources are not ranked, and nothing here is ordered by how useful it is.
- Where nothing has been found for a measure, the measure says so on its own
  page rather than leaving the gap to be discovered.

## Citing it

> Aledda, A. *Insider Threat and Risk Architecture (INTRA&trade;)*.
> <https://alessandroaledda.com/intra/>

GitHub reads `CITATION.cff`, so the **Cite this repository** button on this
page will give you the same thing in a form your reference manager
understands.

`intra.json` is published with its checksum, so the copy you cite can be
checked against the one that was published:

```
curl -sO https://alessandroaledda.com/intra/intra.json
curl -s https://alessandroaledda.com/intra/intra.json.sha256 | sha256sum -c
```

The same digest covers `intra.json` in this repository: the two are the same
bytes.

## Licence and the name

The content is under [CC BY 4.0](LICENSE): use it, change it, build on it,
including commercially, as long as you credit it.

The licence does not cover the name. See [TRADEMARK.md](TRADEMARK.md).

## Contributing

The record grows by contribution and by argument. What a contribution has to
satisfy is in [CONTRIBUTING.md](CONTRIBUTING.md), and the short of it is that
a row is only as good as the source somebody has actually read.

Named so far, with thanks:

- **Jiří Hološka** — The first Czech source in the library, and the map of the
  Czech and Slovak statutes that will follow it.
- **Simon Ball** — Pointed out that MD018 could be read as a capability rather
  than an exception. Its definition now states that the prior suspicion is
  what permits the observation, not what it is for.
- **Benedetto Paolucci** — Pointed at Directive 2022/2557 and at the Board's
  guidance on securing personal data, and asked where the record governs
  physical access rather than watching it. DP016 exists because it did not.

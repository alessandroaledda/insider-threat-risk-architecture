# Schema

Two files, generated from `intra.md` and `library.md`. Nothing is written into
them by hand, so a correction goes to the markdown and not to the JSON.

## intra.json

At the top: `name`, `description`, `author`, `canonical`, `license`,
`license_name`, `release`, `reviewed`, `source_commit`, and `counts`, which
totals the cells by state.

`release` is the release number, in the sense the section on versioning below
sets out, and it is what a citation should carry. `reviewed` is the date the
record was last gone over. `source_commit` is the commit the two markdown
files were at when the file was generated, so a copy can be traced to the text
it was built from.

`version` holds the same date as `reviewed`. It is a name given before there
was a release number to give, it is kept so that anything reading it keeps
working, and it goes at the next major.

`jurisdictions` is the list of the orders in scope, each `{ code, name }`. Two
of them, `EU` and `CoE`, are legal orders and not territories: what each
establishes applies in the states that belong to it, and the two memberships
are not the same.

`pillars` is the list of structural components. Each carries:

| field | |
|---|---|
| `code` | two letters, `GV`, `PS`, `DP`, and so on |
| `name` | |
| `summary` | what the pillar holds |
| `canonical` | where it lives on the site |
| `measures` | the measures under it |

A **measure**:

| field | |
|---|---|
| `id` | the pillar code and three digits, `GV001`. Stable: measures are added at the end of a pillar and never renumbered, because the id is an address |
| `name` | |
| `what` | what the measure is, and what would count as having it |
| `canonical` | |
| `added`, `updated` | dates |
| `cells` | one per jurisdiction that has said something |
| `pending` | sources known to bear on the measure and not yet worked in |
| `guidance`, `research` | sources that speak to it without binding |

A **cell** is the measure as one jurisdiction has it:

| field | |
|---|---|
| `id` | the control identifier, `GV001/EU`, on a binding row and empty on any other, since a standard and a study are cited by their own reference |
| `standing` | `mandatory`, `recommended`, or `reported`: what the row weighs, taken from the kind of the strongest source under it |
| `jurisdiction` | the code |
| `state` | `established` where a source that has been read sets the condition |
| `requirement` | what that source establishes for this measure |
| `sources` | each with `anchor`, `title`, `establishes`, and `url` |

## sources.json

`sections` groups the sources by kind, with the order each is kept in.
`entries` holds them, each with the anchor the record cites it by, its title,
its issuer, its jurisdiction, its date, the address, what it establishes, and
a `status` note where something qualifies the document: superseded, no version
history, only a mirror resolves.

## Versioning

A release number is there to tell whoever cited the record whether their
citation still holds. It says nothing about how much work went into the
release.

| | |
|---|---|
| **major** | An existing reading breaks. A measure or pillar code retired or reused, a definition changed so that the rows under it now assert something else, a change to the vocabulary of states, a change to the shape of either JSON file. |
| **minor** | The framework grows or is restated, and nothing already published changes meaning. A pillar, a measure, a jurisdiction opened, a definition sharpened without altering what its rows assert. |
| **patch** | The record grows or is corrected. Rows, library entries, a source read again, an address that moved, an annotation clarified, a typo. |

This departs from semantic versioning in one place, and on purpose. There,
everything additive is a minor, which would put a single new row and a tenth
pillar on the same step. The record is living and rows arrive continuously, so
the number is more use when it separates the structure that gets cited from
the content that accumulates under it.

The site that publishes the record does not take a version from here and does
not give one: how the pages look changes nothing anyone has cited.

The release is written in three places and they are changed together: the tag
on this repository, `version` in `CITATION.cff`, and `release` in `intra.json`.

## Using it

Both files are CC BY 4.0. `attribution` in each carries the string to credit.

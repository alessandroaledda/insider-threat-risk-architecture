# Schema

Two files, generated from `intra.md` and `library.md`. Nothing is written into
them by hand, so a correction goes to the markdown and not to the JSON.

## intra.json

At the top: `name`, `description`, `author`, `canonical`, `license`,
`license_name`, `version`, `reviewed`, and `counts`, which totals the cells by
state.

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

## Using it

Both files are CC BY 4.0. `attribution` in each carries the string to credit.

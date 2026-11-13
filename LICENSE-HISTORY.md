# Licence history

MeshKit is published under the Functional Source License, Version 1.1, ALv2 Future License
(**[FSL-1.1-ALv2](./LICENSE)**). Each release converts to
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) on its second anniversary.

MeshKit did not start there, so this file records where the boundary falls.

| Scope | Licence | Apache-2.0 from |
|---|---|---|
| Commits up to and including `979ea69` (2026-09) | MIT | already permissive |
| Everything from the relicensing commit (2026-10-01) onward | FSL-1.1-ALv2 | two years after each release |

## The MIT history stands

Commits published under MIT remain available under MIT to anyone who holds a copy of them.
Relicensing binds future versions only. It is **not** retroactive, and nothing here claims
otherwise. What the change does is stop anyone taking the storefront, the Stripe fulfilment
pipeline or the Meshy generation pipeline *as it exists from now on* and selling a competing
product with it — that is the Competing Use clause in [LICENSE](./LICENSE).

## What the pack assets are licensed under

A separate question, and the code licence has never governed it. Generated models ship with
their own `LICENSE.txt` inside each pack — the MeshKit royalty-free asset licence, whose text
is [`src/MeshKit.Pipeline/Licenses/meshkit-standard.txt`](./src/MeshKit.Pipeline/Licenses/meshkit-standard.txt)
and which the store serves at `/packs/<slug>/licence`. Changing the code licence does not
change what a buyer may do with the models they bought.

## How this gets updated

When a versioned release is cut, append a row with the semver tag, the date the tag was
pushed (`YYYY-MM-DD`), and that date plus two years. Pack release tags (`pack/<slug>/<run>`)
are asset artifacts, not code releases, and do not belong in this table.

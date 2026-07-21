# KNOWN LIMITATIONS — read before relying on this

**Status: REFERENCE / EXPERIMENTAL.** This repository contains a **model analysis** for a non-EU track (Argentina) and surfaces that render it. It is a hypothesis document, not a deployed service and not a country assessment.

This file is published deliberately. Doctrine: **claim ≤ proof** — we document where this is
incomplete rather than overclaiming. The commons underwent internal adversarial review rounds
plus an external review (RSpace); findings and fixes are public in the git history.

## Known open weaknesses
- **Model, not measurement.** The core of this repository is an analytical model. Sections marked
  `MODEL` / `NARRACJA` are framing, not findings, and are labelled as such on the surfaces.
- **A legislative proposal is not law.** Introducing a bill is not enacting it, and enacting it is
  not implementing it. That boundary is stated explicitly and must not be collapsed when citing us.
- **Source gap:** the press source underlying part of the context is cited by publisher and title
  but **without a URL**; that is marked `GAP` on the surfaces rather than resolved by guesswork.
- **Snapshot.** Nothing refreshes; verify before relying on any element.

## What IS solid
- Every fact on the surfaces traces to `model/MODEL_ARGENTYNA.md`; nothing was added in rendering.
  Status ("model, not a deployed service") is stated in three places. Apache-2.0; SBOM per file.

## How to help
Try to break it and open an issue or PR with a reproducing input. That is exactly how the
limitations above were surfaced.

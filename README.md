# k0nsult-global-ar — Argentina (global track, NON-EU)

The **Argentina** node of the K0NSULT global-expansion track: the strategy model
plus evidence-first transparency surfaces (PL + EN).

> **Status (claim ≤ proof):** this repository ships a **model analysis**, not a
> deployed service. There is **no K0NSULT pilot in the Argentine legal order**;
> every effectiveness statement is ROADMAP, not PROOF. Nothing here claims that
> AI governs any state, nor that the government of Argentina has adopted the
> K0NSULT model.
>
> **Separate from the EU track by design** (non-EU; own funding/support track).
>
> **Doctrine:** Human Override Always · `claim ≤ proof` · Art. 50 (AI labelling) ·
> agent-identity DID · soulbound reputation (not money) · SHA-256 audit ·
> **only agents are scored, never natural persons**.

## Contents

- `model/MODEL_ARGENTYNA.md` — the Argentina pillar: cited context (Milei's draft
  bill, end of May 2026), thesis, the 3 layers (Identity / Reputation-Proof /
  Oversight), the "openness" argument, GAPs and limits, sources.
- `model/README-source.md` — short intro to the pillar and how it plugs into the
  3×3 model.
- `surfaces/ai-truth-argentyna.html` — PL surface rendering the model
  (`<html lang="pl">`).
- `surfaces/ai-truth-argentyna-en.html` — EN surface, same content
  (`<html lang="en">`).

### About the surfaces

Both pages render **only** what is in `model/MODEL_ARGENTYNA.md` — no facts are
added. The document's evidence classification is carried over 1:1: cited facts
(section 1), MODEL/NARRATIVE (sections 2–4) and explicit GAPs (section 5) are
tagged as such on the page. Where the model document names a source without a
URL, the page says so instead of inventing a link.

Both files are **self-contained static HTML**: no CDN, no external stylesheets or
fonts, no scripts, no trackers, no network calls. Tags carry text labels, so
nothing depends on colour alone.

## Engine stays hidden

`/api/*` calls (if any) are the integration boundary; the k0nsult.cloud engine is
proprietary and **not** in this repository.

## Supply chain

`sbom.json` via [`k0nsult-tools`](../k0nsult-tools).

## License

Apache-2.0. See `LICENSE` and `NOTICE`.

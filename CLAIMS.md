# CLAIMS.md — public claim register (k0nsult-global-ar)

Generated from [`k0nsult-tools/docs/CLAIMS-TEMPLATE.md`](https://github.com/0n40i4/k0nsult-tools/blob/master/docs/CLAIMS-TEMPLATE.md)
(OSS-0-06). This repo already carries an exemplary claim<=proof self-declaration
(README.md:6-10) — this file makes it machine-tabular rather than restating it.

| id | statement | class | proof_ref / roadmap_ref | repo_status_ref | verified_at |
|---|---|---|---|---|---|
| `clm-0001` | This repository ships a model analysis, not a deployed service; there is no K0NSULT pilot in the Argentine legal order. | GAP | `README.md`:7-8 (repo's own explicit self-classification, verbatim: "this repository ships a **model analysis**, not a deployed service. There is **no K0NSULT pilot in the Argentine legal order**") — this is the repo declaring its own status as ROADMAP, not proof | — | 2026-08-02 |
| `clm-0002` | Every effectiveness statement in this repo is ROADMAP, not PROOF; nothing claims AI governs any Argentine state function or that the government of Argentina has adopted the K0NSULT model. | GAP | `README.md`:8-10 (verbatim: "every effectiveness statement is ROADMAP, not PROOF... nor that the government of Argentina has adopted the K0NSULT model") | — | 2026-08-02 |
| `clm-0003` | The two HTML surfaces (`surfaces/ai-truth-argentyna.html` PL, `surfaces/ai-truth-argentyna-en.html` EN) render only content present in `model/MODEL_ARGENTYNA.md`, with the source document's own evidence classification (cited facts / MODEL-NARRATIVE / GAPs) carried over 1:1. | DOWOD | `README.md`:32-36 (design rule stated in-repo) + file presence: both surface files and `model/MODEL_ARGENTYNA.md` exist in this checkout | — | 2026-08-02 |
| `clm-0004` | Both HTML surfaces are self-contained: no CDN, no external stylesheets/fonts, no executable scripts, no trackers. | DOWOD | Independently checked, not just quoted from README: `grep -ico "<script" surfaces/ai-truth-argentyna*.html` → 1 match each; `grep -n -A2 "<script"` shows the single tag in each file is `<script type="application/ld+json">` (inert JSON-LD structured data, not executable code). `grep -o 'https\?://...'` finds only `k0nsult.cloud`/`schema.org` URLs used as referential identifiers inside that same JSON-LD block (canonical URL, publisher, breadcrumb) and in `<meta>` tags (e.g. `og:image`) — none are `fetch`/`<script src>`/`<link>` calls a loaded page would execute. | — | 2026-08-02 |
| `clm-0005` | This repo's proposed `x-k0nsult.status` is ROADMAP — the family's most direct self-to-canonical-enum match of any of the 11 repos (README already used the word "ROADMAP" verbatim before this rollout existed). | DOWOD | `README.md`:8 ("ROADMAP, not PROOF") + `../k0nsult-eu-shield/generator.config.yml` records `status: ROADMAP` for this repo (OSS-1-06 proposal); writing it into `publiccode.yml` is still Fala 1, WYMAGA_ACK: TAK | `k0nsult-global-ar#x-k0nsult.status` | 2026-08-02 |

## Placeholder row (copy for new claims)

| id | statement | class | proof_ref / roadmap_ref | repo_status_ref | verified_at |
|---|---|---|---|---|---|
| `clm-00NN` | *(exact claim text)* | *(DOWOD\|GAP\|NARRACJA)* | *(ref, or "—" if NARRACJA)* | *(optional, or "—")* | *(YYYY-MM-DD)* |

| clm-0006 | GAP | `publiccode.yml` (x-k0nsult.manifest.hash / sbom.hash) wskazuje na hash `sbom.json` sprzed regeneracji w tym PR — po merge będzie niezgodny mimo deklaracji `evidence_class: DOWOD`. Generator `gen-publiccode.mjs` nie istnieje w żadnym dostępnym repo (sprawdzone: to repo, k0nsult-tools) — nie da się przeliczyć bez fabrykacji. Wymaga ręcznej naprawy przez kogoś z dostępem do generatora, albo świadomego obniżenia evidence_class do czasu naprawy. | recenzja Fala 4, 2026-08-16 |

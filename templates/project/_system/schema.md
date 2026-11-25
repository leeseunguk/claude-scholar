# KB Schema

## Project Scope
All project knowledge belongs to `Research/{{project_slug}}/`.

## Directory Rules
- source-centered notes stay under `Sources/*`
- cross-source synthesis stays under `Knowledge/`
- experiment design and run tracking stay under `Experiments/`
- stable findings stay under `Results/`
- round and batch reports stay under `Results/Reports/`
- prose deliverables stay under `Writing/`
- process notes stay under `Daily/`
- derived artifacts stay under `Maps/`
- archived notes stay under `Archive/`

## Source vs Knowledge
- `Sources/*` is for source-centered notes
- `Knowledge/` is for durable synthesis across one or more sources
- do not use `Knowledge/` as a second raw-source inbox

## Raw Data and Files
- Do not copy original documents, raw datasets, or code outputs into the project.
- Record the original location, and a data hash or code commit hash in each note that depends on it.

## Question Folders (optional)
If the project is split by research question, use `Topics/<topic>/` with `Knowledge/`, `Questions/`, and `Results/` inside. Otherwise keep the default folders above.

## Record Density
- Create an `Experiments/` run card only when a result is used as a number in a claim or report.
- `Daily/` gets one or two lines per day.
- Full rules and report triggers: `references/RECORD-DENSITY.md` in the obsidian-project-kb-core skill.

## Claim Promotion Gate
- A claim goes into `Results/` (or a claims folder) only when a run card or `Sources/` note supports it through a link.
- When sources disagree, write both values, mark `(확인 필요)`, and add the item to the unresolved list in the index.

## Registry Rules
`_system/registry.md` is the only visible project registry.
Keep human-maintained fields stable across sync. Deterministic sync should update paths and timestamps, not rewrite curated metadata.

## Index Rules
`02-Index.md` is a human-readable MOC, not a registry mirror.
Only the auto-index block is regenerated automatically.

## Hub Rules
`00-Hub.md` should only receive small status-oriented updates. Do not rewrite the whole note during routine sync.

## Daily Promotion Rules
Durable insights discovered in `Daily/` should be promoted into `Knowledge/`, `Experiments/`, `Results/`, or `Writing/` when they become reusable.

## Archive Rules
- note archive lives in `Research/{{project_slug}}/Archive/`
- project archive lives in `Research/_archived/`
- archive history stays visible in `_system/registry.md`

## Map Rules
`Maps/` contains derived navigation artifacts only. Do not treat maps as the project source of truth.

## Cross-project Rules
Do not move notes, merge registries, or synthesize across multiple `Research/{project-slug}/` roots unless the user asks for explicit cross-project work.

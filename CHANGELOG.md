# Changelog

## 13.0.0 — 2026-08-03

### Architecture

- Rebuilt the skill as a narrative-first, stateful production system.
- Added input routing for rules, story, assets, mixed tasks, and revisions.
- Added project, story, asset, continuity, and commercial-admission anchors.
- Split the monolithic prompt corpus into task-specific references.

### Filmmaking

- Added blocking, motivated camera, axis, eyeline, screen direction, cut-point, performance, lighting, and sound logic.
- Replaced fixed shot counts with narrative-density and model-stability decisions.
- Removed the rule that every shot must move.
- Removed the fixed food-prop transition.
- Added actionable Sequence overload and underload checks.

### Intimacy direction

- Replaced position-keyword assembly with consent-aware choreography, body geometry, contact maps, reaction chains, transition paths, wardrobe state, and aftercare.
- Removed forced onomatopoeia from the active execution path and moved repeated explicit prompt recipes out of the default context; the original company materials remain recoverable in historical commit `f2553bbba898331ed021095338ea638ce70ff01b`.
- Added a strict adults-only, consensual, authorized-content gate.
- Added research language that separates observable performance from psychological diagnosis.

### Model adapters

- Rebuilt Seedance 2.0 guidance around official multimodal reference capabilities.
- Added explicit `@asset` responsibility mapping.
- Added generation, extension, editing, first/last-frame, audio, and degradation strategies.
- Removed unverified hard-coded model IDs and universal API assumptions.

### Commercial delivery

- Added rights-chain checks, model/platform verification, continuity QA, manifest fields, file naming, and handoff package requirements.
- Added acceptance tests.
- Added an actual MIT `LICENSE` file.
- Synchronized README and Skill versions.

## 12.x

Legacy monolithic version containing script, storyboard, asset, model, emotion, position, sound, and prompt-corpus rules in one file. The original files remain preserved in Git history at `f2553bbba898331ed021095338ea638ce70ff01b`; they are not part of the v13 default load path.
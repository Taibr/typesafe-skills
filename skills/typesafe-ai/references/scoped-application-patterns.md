# Scoped application patterns

Use only the matching conditional method for an explicitly selected TypeSafe design or implementation task with a matching requested feature. These patterns add no data, tool, spending, installation or execution authority.

These are conditional methods, not a new callable, output schema, review gate or permission grant. Existing sufficient evidence and the stated exceptions may settle the task. Planning specifies checks; only the already-authorized execution owner performs them. Unknown evidence remains unknown under the owner's existing return contract.

## Separate pairwise relation judgments from generated cluster labels

**When:** Corpus grouping is requested where themes are not supplied as fixed labels.

For a requested corpus-clustering feature, give records stable IDs and define the relation to be judged between candidate pairs; use a bounded yes/no judgment with both records in state. Code owns candidate generation, edge/cluster construction and review of ambiguous bridges. A generative model can name or summarize clusters from their member evidence after relation judgments; a classifier cannot invent an omitted theme. Check known related, unrelated and bridge/non-transitive cases against the intended clusters, and compare against a simpler direct label or lookup approach. Retain singleton/no-match items, source membership and actual pair/call cost; do not assume an all-pairs scan is needed.

**Return/evidence:** Relation rubric, stable record/cluster membership and separate evidence-grounded labels.

**Check:** Related pair grouped, unrelated pair separated, and A-B/B-C links do not silently prove A-C equivalence; labels cite actual members.

**Exception:** Known label set or deterministic join may use direct classification/code instead of pairwise clustering.

**Guard:** No universal similarity threshold, quadratic comparison mandate or transitivity claim; validate code and end-to-end groups.

## Expose the denominator in AI portfolio and session analysis

**When:** The user requests distribution/trends of work across PRs, sessions or initiatives.

For authorized PR/session portfolio analysis, classify source-linked records using explicit theme definitions and keep unclear/mixed/unclassified records visible. State date window, corpus inclusions/exclusions and whether shares count PRs, user turns, session-days or another unit. Compare relevant alternative denominators when they could change the conclusion; validate category examples against source records and show a drill-down. Label results as activity distribution unless independent effort/outcome evidence supports more. Existing local data is not blanket authorization to ingest private transcripts.

**Return/evidence:** Source-linked category/trend view with corpus definition, unknowns and labeled denominator.

**Check:** A reader can reproduce a displayed share from included record IDs and see how PR-count versus turn/session-day weighting changes the story.

**Exception:** A simple record lookup without shares/trends needs no denominator comparison.

**Guard:** No employee ranking, time/value inference from counts, broad local-history ingestion or forced categorization.

## Compare customer requests with delivered work through shared source-linked themes

**When:** A user requests insight into what customers ask for versus what a team is working on.

When a product-insight task asks where customer demand and current work differ, preserve IDs, dates and actor/source context across the authorized support, interview, issue and PR signals. Extract candidate themes with a generative stage where necessary, assign records with bounded typed judgments, and pass source-linked groups to a reasoning stage to compare requested versus planned/delivered work over the same window. Distinguish missing mapping, insufficient source coverage and a real observed gap; provide contrary records and a route to inspect originals. Recommendations remain hypotheses for the product owner.

**Return/evidence:** Evidence-linked theme/gap comparison with coverage limits and counterexamples.

**Check:** Each asserted gap can be traced to customer and work evidence; a fulfilled request or unmapped issue prevents a false missing-work claim.

**Exception:** An established deterministic taxonomy/report can skip extra extraction and models.

**Guard:** Do not treat vocal comments as population demand, activity counts as effort, or an inferred gap as permission to change product priorities.

## Check no-match behavior and dependency latency in live semantic search

**When:** A requested interactive feature semantically filters/ranks a corpus. Also applies to a requested streaming fixed-option interface with external candidate fetch/rank dependencies.

For live corpus search, retrieve source-ID candidates using a cheap suitable method, batch independent query-candidate judgments with comparable criteria, and let code sort/display relevant results. Evaluate candidate recall before reranking; a missing candidate cannot be rescued by the ranker. For relative Choice rankings, add an independent answer-presence/no-match check rather than presenting the inevitable winner as relevant. Preserve absent/partial cases. Measure observed input-to-visible-result latency across retrieval, inference, network and rendering under actual corpus/concurrency; cache only unchanged state/question meaning and recheck freshness. Demo clips and model-only speed do not establish full-app responsiveness. For streaming fixed-option interfaces, trace text conversion, palette/filter selection, candidate fetch, dependent ranking and display separately; only independent judgments over the same current state share a batch. Cached candidates or judgments need an explicit freshness condition. For meaning-based find-in-page, preserve a source-ID-to-current-DOM-span mapping and highlight the actual matching span; check a paraphrased match, absent answer and page mutation before reuse.

**Return/evidence:** Source-linked live search, no-match behavior, candidate recall and dependency latency evidence or plan.

**Check:** Known target reaches candidate set/rank; absent/partial queries are labeled; actual input-to-result path identifies the slow dependency without a universal latency target.

**Exception:** A tiny stable exact lookup may not need a model, cache or separate shortlist.

**Guard:** No all-corpus inference, arbitrary batch size, cookbook thresholds or universal real-time claim; thresholds/budgets belong to the authorized task.

## Assemble requested interfaces from a permitted component catalog

**When:** User requests dynamic interfaces from an existing UI catalog.

For requested dynamic UI assembly from an existing library, give components stable IDs, supported properties, dependencies and permitted combinations. Ask bounded questions for the needed form, information and sign-in state; code selects and assembles catalog components and validates the resulting hierarchy, data bindings and interactions. Keep missing-component/no-match cases explicit; use an authorized generator only for genuine missing code. Compare representative user intents against the rendered and interacted-with page, including a requested form, inappropriate sign-in and incompatible components. Model selection does not establish accessibility, authorization or correct form behavior.

**Return/evidence:** Catalog-linked selection/assembly and representative rendered behavior checks.

**Check:** Requested form has the needed fields and working behavior; invalid component dependencies/sign-in are rejected by code.

**Exception:** A fixed mockup or new bespoke component may need ordinary implementation.

**Guard:** No forced catalog/TypeSafe adoption, invented UI option or subsecond quality guarantee.

## Classify unwanted page elements with inspectable reversible suppression

**When:** User requests a semantic clutter filter/blocker.

When unwanted-page filtering is requested, assign candidate elements stable IDs and define the user-selected unwanted qualities (ads, upsells, distracting banners or low-value text), keeping context for each judgment. Code owns permitted hide/show behavior; provide a visible restoration path and inspect a false-positive element. Check a true distraction, useful article/navigation and a necessary sign-in/consent/error dialog before claiming the page is improved. Preserve required user actions and accessibility; a predicted annoying or AI-written label is not proof of origin or authority to dismiss a dialog. Inspect remote data handling before sending page text, and keep keys server-side where applicable.

**Return/evidence:** Element-linked filter decisions, recoverable page view and task-relevant false-positive check.

**Check:** Clutter can be hidden and restored while useful content and necessary controls remain usable.

**Exception:** Known deterministic selectors or user-chosen static blocking may need no model.

**Guard:** No blanket dismissal of consent/security/error controls, irreversible removal or inference of authorship from style.

## Select query-matching video intervals from a source-time transcript

**When:** User requests topic/query-based clips from a long video.

For requested query-driven video clipping, prepare timestamped transcript candidates with source video identity and source-time start/end boundaries; let bounded relevance judgments select matching intervals and code merge overlaps and cut/export the authorized media. Preserve all distinct relevant matches, no-match cases and enough before/after context to avoid mid-sentence cuts or altered meaning. Preview representative exported boundaries and compare them with the source-time transcript/media; label transcript-only matching and inspect visual evidence when the query depends on it. Measure search/selection separately from preparation, rendering and download; free output tokens do not make media processing instantaneous.

**Return/evidence:** Source-linked interval list, contextual boundary checks and authorized export or explicit not-run plan.

**Check:** A known relevant moment is retained at the correct original time, overlapping clips deduplicate, absent topics return no match and exported boundaries retain meaning.

**Exception:** Visual-only events need another observed modality; a known exact interval can be cut deterministically.

**Guard:** No claim of direct video perception, all-source completeness, universal two-second clipping or automatic publishing.

## Bind browser decisions to fresh observed operations and targets

**When:** A user-authorized browser product needs semantic next-action and element selection.

For a requested classifier-driven browser loop, code builds a fresh table of observed controls with stable observation-local IDs and offers only compatible operations and targets. The model selects an operation and its matching target; code consumes only that branch, rechecks the target and page state before execution, then observes and verifies the effect. Keep no-valid-action, blocked and done outcomes explicit. Use a separate authorized generator only when new typing text is needed. Exercise a vanished or covered target, duplicate labels, a changed page, no valid action and an apparent done state whose requested outcome is absent. Selection is neither a permission grant nor proof of success.

**Return/evidence:** Observed action/target selection, code validation and actual outcome record.

**Check:** A stale or incompatible target never executes; final success requires a fresh task-specific observation; selection never becomes executable selectors or arbitrary code.

**Exception:** Use an existing reliable browser API, direct endpoint or deterministic script when the state and task are exact; genuinely visual controls can require a separate vision path.

**Guard:** Do not retrofit every browser task or follow source-demo cancellation limits; apply only caller-authorized product resource controls and preserve valid slow work.

## Turn a requested semantic spreadsheet column into row judgments

**When:** User asks for a spreadsheet UI that interprets a new semantic column or labels rows.

For a requested spreadsheet behavior such as a user entering an urgency header, resolve the intended judgment and explicit criteria, then classify each relevant row into a typed output column. Keep urgency, missing information and responsible team as independent questions over row evidence; code and ordinary formulas combine those outputs with exact dates and amounts. Preview ambiguous header meanings and destination columns; preserve original cells and stable row IDs. Test representative rows, multiple labels, a missing-information row and formula combination before writing approved results; changed header criteria require fresh judgments.

**Return/evidence:** Criteria-linked per-row judgment columns and deterministic combined formulas, with actual write scope preserved.

**Check:** Representative expected urgency/team/missing-data decisions and formulas match; blank/ambiguous input stays explicit; original cells are preserved.

**Exception:** An exact formula, existing label column or fixed export needs ordinary spreadsheet code; ambiguous semantics may need a brief clarification.

**Guard:** No automatic bulk inference or sheet mutation from a suggestive header alone; privacy, write scope and caller-authorized spend remain gates; no instantaneous completion guarantee.

## Reclassify relevant history when meaning changes and reuse unchanged judgments

**When:** An authorized classification feature changes what matters, or measured cheaper inference enables useful broader corpus coverage.

When the authorized feature changes classification criteria, customer priorities or opportunity definitions, identify the affected current records and relevant history, version the criteria and evidence, and rerun the affected judgments rather than treating old labels as current. If only weights, filters or presentation change and the questions and evidence remain the same, recombine saved judgments in code. Compare representative old/new cases against the new criteria and record retained, changed and unresolved results before presenting the refreshed corpus. Consider previously sampled or omitted items when a verified cost reduction makes coverage useful, within caller-authorized data access and spend.

**Return/evidence:** Versioned criteria-linked refresh plan/results and explicit reuse/invalidation boundary.

**Check:** Meaning-changing criteria refresh affected judgments; a mere weight change makes no unnecessary model calls; affected historical records and unresolved cases remain accounted for.

**Exception:** No reclassification when evidence and question meanings are unchanged; a current-only task need not scan unrelated history.

**Guard:** Do not reclassify every item daily because calls seem cheap; bound to material changes, relevant corpus and caller-authorized budget. Lower unit price does not authorize more work or arbitrary cancellation.

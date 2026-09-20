# Documentation Conventions

**Type: Authorial guide**

**Status: Active**

This guide owns the project's filing, status, language, linking, and maintenance rules. It establishes no fictional canon.

## Corpus Boundary

Agents and LLMs must not write, rewrite, or edit corpus prose, including drafts, fragments, fictional documents, and equivalent creative text stored elsewhere. This material remains entirely user-written. Read and discuss it only when requested, providing critique or suggestions without modifying the source.

Apply this boundary by content role regardless of location or file type. Exclude corpus text from formatting passes, automated link repair, template application, and content migration. An organisation request does not itself request a reading or critique of creative text.

## Local Organisation

The following locations currently exist:

| Location | Responsibility |
| --- | --- |
| Root | Entry page, short agent instructions, and documentation conventions. |
| `00 Core` | Premise and durable design constraints. Add story intent, terminology, or inspirations only when there is material to record. |
| `99 Workshop` | Development queue, method, deferred later scenarios, and the compact integration inventory. Stable setting detail belongs in topical owners. |
| `01 World` | Geography, environments, history, places, and local infrastructure conditions. |
| `10 Technologies and Infrastructure` | Recurring capabilities, dependencies, maintenance, and constraints. |
| `11 Society` | Communities, institutions, governance, economy, culture, and ordinary life. |
| `12 People` | Concise profiles of historical people and fictional figures, separating documented background from in-setting portrayal. |
| `97 Assets/Source Archive` | Immutable source snapshots for provenance, superseded by current topical references. |
| `98 Temp` | Temporary planning material, including the integration progress plan. |
| `.obsidian` | Existing editor settings, themes, and plugins. Preserve their native format and state. |
| `.agents` and `.codex` | Existing agent configuration locations. Preserve unless changes are requested. |

The following expansion map remains available when content needs it:

| Future location | Responsibility and boundary |
| --- | --- |
| `80 Narrative` | Author-facing story-specific viewpoints, relationships, arcs, and scene planning. |
| `90 Corpus` | The author's creative prose and drafts, protected by the corpus boundary. |
| `97 Assets` | Supporting attachments, such as images and PDFs. Keep important reference prose in a topical note. |

Keep fixed `00 Core` and `01 World` first, followed by the project-specific domains in slots `10`, `11`, and `12`. Add further domains before `80 Narrative` only when useful. Creating attachment or temporary folders does not authorise changes to editor settings.

Folders identify responsibility, not approval. Use descriptive filenames and deliberate reading order. Add subfolders when actual material benefits from grouping. Do not invent content to populate a structure. Separate recurring mechanisms from their applications when each warrants its own owner.

## Ownership

One document owns each detailed answer. Other notes provide enough context to be readable and link to that owner. Keep specialised definitions with their subject and link them from a glossary if one becomes useful.

Keep detailed setting questions with the topic. The revision queue owns work order and deferral. [[99 Workshop/Research/Research Topics|Research Topics]] lists bounded investigations and their inputs. Research and calculation notes own supporting analysis, while setting references record selected results and their limits. Split by independent purpose or retrieval, not length alone.

[[00 Core/01 Premise|Premise]] owns the selected foundation and open narrative boundaries. [[00 Core/02 Axioms|Axioms]] owns design constraints. Topical notes own detailed setting context and their unresolved questions. [[00 Core/03 Integration Decisions|Integration Decisions]] records the scope of the handoff adoption.

[[12 People/00 People Guide|People Guide]] owns the compact person-profile format. A profile owns a person's summary, not the research evidence, institutional mechanics, or story-specific arc. For real people, distinguish documented history from in-setting choices. For inspired or fictional people, keep source material and author-selected facts distinct from invented proposals.

## Status and Approval

Begin ordinary author-facing notes with one descriptive title and separate **Type** and **Status** paragraphs. Use **Scope**, **Approval**, **Development**, or source fields only when they clarify a meaningful boundary. Preserve native board formats and do not add labels to corpus text.

| Label | Meaning |
| --- | --- |
| `Current foundation` | Continuity with the surviving premise and axioms, within their stated scope. It grants no approval to new details. |
| `Current direction` | An author-selected but revisable narrative direction. |
| `Exploring` | Alternatives under consideration. |
| `Provisional` | A working proposal awaiting selection. |
| `Selected baseline` | Material explicitly selected by the author, with its scope and decision evidence recorded. |
| `Unassessed` | Inherited material whose authority has not been established. |
| `Active` | An operating guide, index, or queue. This describes use, not canon status. |

Use `Development: Explicitly deferred` for postponed work without replacing its existing approval status. Retained rejected or superseded material needs a stated scope and, where applicable, a link to its replacement. An active queue can contain only deferred items.

Keep authorial selection, development state, in-setting availability, and evidence separate. Use section-level labels for mixed material. Never infer approval from location, polished wording, a file move, or inclusion in navigation. Preserve conflicting names, figures, and assumptions until an authorised decision resolves them. An unresolved detail does not automatically invalidate every related selected fact.

## Writing and Knowledge

Use clear, direct authorial reference prose in Canadian English. Prefer concrete verbs, connected paragraphs, consistent terminology, and meaningful qualifications. Minimise em dashes and semicolons. Remove empty framing and contrasts that add no information. Use headings for retrieval, lists for parallel items, and tables for useful comparisons.

Preserve French names and accents, official titles, source spellings, quotations, and intentional multilingual text. Do not infer the narrative's language, dialect, or voice from the setting. These remain authorial choices.

Keep objective reality, institutional knowledge, common practice, common belief, and narrative revelation distinct. An author's complete explanation does not establish what characters can know. Fictional letters, journals, and other creative documents remain corpus text.

Distinguish sourced facts, scenario assumptions, inferred consequences, and selected fiction. Record source, publication date, geographic and temporal scope, and limitations when they affect a claim. State units, assumptions, and uncertainty in calculations. Research findings do not automatically establish disaster conditions or fictional outcomes. When critique is requested, identify the draft assessed so historical feedback remains distinguishable from current assessments.

## Links and Formatting

Prefer Obsidian wikilinks with vault-relative targets for cross-folder references. Ordinary Markdown links are also supported and use paths relative to the containing file. Use exact filename case and descriptive labels. Keep essential instructions and navigation local to this project.

Use a coherent heading hierarchy. Preserve intentional formatting, equations, code fences, frontmatter, and plugin-managed syntax. Link at useful first occurrences and to headings when helpful.

Omit item-final full stops, commas, and semicolons in bullet points and comparable lists. Keep short items together without blank lines between them. Use blank lines when long sentences or paragraphs warrant the extra separation. Preserve punctuation within items and in quotations. Apply this convention within the authorised editing scope and corpus boundary.

In Markdown tables, escape every pipe belonging to cell content with exactly one backslash: `\|`. This includes inline code and Obsidian labels such as `[[Target\|Label]]`. Leave structural column separators unescaped. Outside tables, use `[[Target|Label]]`. Check cell counts after table edits and adjust escaping when moving text into or out of tables. Link examples in code spans are illustrative, not navigation targets.

## Changes and Handoff

Follow the user's authorised scope and preserve unrelated work. Organisation changes do not resume explicitly deferred development. Preserve existing `.obsidian`, `.agents`, and `.codex` state unless changes are requested.

The imported handoff is retained as an archival source snapshot, not a parallel setting reference. When source material is superseded, account for its useful information, authority, and provenance before moving or removing it. Review markers and temporary locations do not make content disposable.

Update links, heading targets, navigation, and ownership statements together within editable author-facing documentation. Report affected corpus references for the user to update. When a foundational decision changes, trace direct and likely indirect consequences through dependent notes. Surface substantive contradictions rather than selecting answers solely to make files agree.

Before handoff, apply the validation scope below and verify affected approval, provenance, and deferral boundaries. Check new files as well as existing edits. Report checks and limitations accurately. `git diff --check` checks whitespace only. File comparisons can verify changes without using Git.

Local guidance must contain its required rules and dependencies without relying on a parent folder, sibling project, absolute workspace path, or external symlink. Check this under the portability conditions below.

## Validation Scope and Stopping Rule

Validate changed material and dependencies that the change could affect. Do not revalidate unrelated content by default. Review the relevant diff or before/after comparison, including new files, for unintended changes and information loss.

| Change | Check |
| --- | --- |
| Ordinary prose correction | Review the edited prose. Skip link checks if targets, headings, paths, and link syntax are unchanged. |
| Link added or target changed | Resolve that link and any heading target. |
| Display label changed | Check syntax and escaping. Recheck the destination only if its target or resolution context changed. |
| Heading renamed or removed | Find and check references to that heading. |
| File moved, renamed, or deleted | Find inbound references and check affected relative links, embeds, navigation, and stale path mentions. |
| Table or structural Markdown edited | Check the affected table's cell counts and pipe escaping, or the affected headings, fences, and surrounding structure. |
| Numerical or foundational content changed | Check the affected values, interpretations, and dependent references within the authorized scope. |

An affected link may be in an otherwise unchanged file. Use a targeted search across editable documentation to find inbound references when needed. This is not a reason to validate every unrelated link. Corpus protection still applies, including during dependency searches.

Batch related edits before checking them. Once a relevant check passes, stop. Repeat only checks whose inputs or dependencies changed, checks needed to investigate an unresolved failure, or checks justified by new evidence or an explicit request. One successful check can satisfy several workflow steps. Do not repeat it merely to produce another handoff summary or report a larger check count.

Broaden validation only when requested or when the actual change or evidence warrants it, such as widespread path changes or failures suggesting a systemic problem. State the reason and limit the scope accordingly. A bootstrap checks the new starter and its local dependencies, not neighbouring projects.

Check portability when guidance is first adopted or when paths, dependencies, or instruction routing change. Inspect the affected guidance and local dependencies first. Use a temporary isolated copy only when it would resolve a concrete uncertainty about external dependencies or when explicitly requested. Ordinary wording edits do not require an isolated copy.

Report the checks actually performed and any relevant limits. Do not maintain validation logs, version fields, or recurring audit dates solely to support this rule.

## Local Adaptations

Adapted from Writing Project Standards using its bootstrap workflow and selected project templates. The initial starter preserved the surviving brief. The author subsequently authorised adoption of the handoff's early setting and design constraints. Topic folders now hold that material, while later scenarios remain deferred.

These rules are self-contained. Later changes to the source model do not automatically change this project. No assumptions about other fictional settings apply here.

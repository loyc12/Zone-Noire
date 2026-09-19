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
| `99 Workshop` | Development queue, method, and future research or comparisons. Selected topical answers belong in their subject owners. |
| `.obsidian` | Existing editor settings, themes, and plugins. Preserve their native format and state. |
| `.agents` and `.codex` | Existing agent configuration locations. Preserve unless changes are requested. |

The following expansion map is available when content needs it. These folders have not been created by the bootstrap:

| Future location | Responsibility and boundary |
| --- | --- |
| `01 World` | Geography, environments, history, places, and local conditions. A place note owns the location and condition of its infrastructure. |
| `10 Technologies and Infrastructure` | Recurring technical capabilities, dependencies, maintenance, and constraints. Link local installations to these mechanism owners. |
| `11 Society` | Communities, institutions, governance, economy, culture, and ordinary life. A community note owns its organisation, with links to its physical location. |
| `80 Narrative` | Author-facing characters, viewpoints, relationships, arcs, and scene planning. |
| `90 Corpus` | The author's creative prose and drafts, protected by the corpus boundary. |
| `97 Assets` | Supporting attachments, such as images and PDFs. Keep important reference prose in a topical note. |
| `98 Temp` | Incidental Obsidian-generated files. Keep valuable work elsewhere and review contents before removal. |

Keep fixed `00 Core` and `01 World` first, followed by the project-specific domains in slots `10` and `11`. Add further domains before `80 Narrative` only when useful. Creating attachment or temporary folders does not authorise changes to editor settings.

Folders identify responsibility, not approval. Use descriptive filenames and deliberate reading order. Add subfolders when actual material benefits from grouping. Do not invent content to populate a structure. Separate recurring mechanisms from their applications when each warrants its own owner.

## Ownership

One document owns each detailed answer. Other notes provide enough context to be readable and link to that owner. Keep specialised definitions with their subject and link them from a glossary if one becomes useful.

Keep detailed open questions with the topic. The revision queue owns work order and deferral. Research and calculation notes own supporting analysis, while setting references record selected results and their limits. Split by independent purpose or retrieval, not length alone.

Until narrower subject notes exist, [[00 Core/01 Premise|Premise]] owns the open setting and narrative boundaries, and [[00 Core/02 Axioms|Axioms]] owns the realism constraint.

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

In Markdown tables, escape every pipe belonging to cell content with exactly one backslash: `\|`. This includes inline code and Obsidian labels such as `[[Target\|Label]]`. Leave structural column separators unescaped. Outside tables, use `[[Target|Label]]`. Check cell counts after table edits and adjust escaping when moving text into or out of tables. Link examples in code spans are illustrative, not navigation targets.

## Changes and Handoff

Follow the user's authorised scope and preserve unrelated work. Organisation changes do not resume explicitly deferred development. Preserve existing `.obsidian`, `.agents`, and `.codex` state unless changes are requested.

No archive collection is currently needed. If source material is later superseded, account for its useful information, authority, and provenance before moving or removing it. Review markers and temporary locations do not make content disposable.

Update links, heading targets, navigation, and ownership statements together within editable author-facing documentation. Report affected corpus references for the user to update. When a foundational decision changes, trace direct and likely indirect consequences through dependent notes. Surface substantive contradictions rather than selecting answers solely to make files agree.

Before handoff, compare the file inventory and changes for information loss, check affected links and Markdown, and verify status and deferral boundaries. Check new files as well as tracked diffs. `git diff --check` checks whitespace only. Use file comparisons when Git is unavailable. Report checks and limitations accurately.

When changing local guidance, verify it in an isolated copy with its local dependencies. Check that links resolve, template tokens are absent, and ordinary work needs no parent folder, sibling project, absolute workspace path, or external symlink.

## Local Adaptations

Adapted from Writing Project Standards using its bootstrap workflow and selected project templates. The surviving premise and axioms retain their wording and status. The starter adds a queue and development method because the premise already points to deferred work. Additional subject folders are reserved for future content.

These rules are self-contained. Later changes to the source model do not automatically change this project. No assumptions about other fictional settings apply here.

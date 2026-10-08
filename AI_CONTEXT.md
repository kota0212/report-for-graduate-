# AI Context / Machine-readable project index

project_id: graduate-thesis  
repository: kota0212/report-for-graduate-  
source_of_truth: this-repository  
reviewed_at: 2026-10-08  
phase: research-scoping  
research_topic: unverified  
research_question: unverified  
research_design: undecided  
university_requirements: unverified  
icloud_inventory: not-accessed  
source_classification: not-performed  
verified_literature_count: 0  
public_repository: true

## Read only what is relevant

- rules: [AGENTS.md](AGENTS.md)
- human_summary: [docs/overview.md](docs/overview.md)
- plan: [docs/research-plan.md](docs/research-plan.md)
- previous_plan_assessment: [docs/plan-review.md](docs/plan-review.md)
- methods_decision: [docs/research-design.md](docs/research-design.md)
- tasks: [docs/tasks.md](docs/tasks.md)
- literature_registry: [references/literature-matrix.md](references/literature-matrix.md)
- evidence_policy: [references/README.md](references/README.md)
- note_template: [references/source-note-template.md](references/source-note-template.md)
- source_notes: [sources/README.md](sources/README.md)

## Invariants

- Do not promote unknown facts to confirmed state.
- Never claim to have moved or read iCloud files unless tool evidence proves it.
- Never upload source PDFs, private academic materials, raw respondent data, or secrets to this public repository.
- Keep human-facing summaries compact and link to canonical detailed documents.
- Maintain literature IDs and task IDs; reconcile state when updating.
- Default to pending for unread literature, especially while RQ remains unresolved.

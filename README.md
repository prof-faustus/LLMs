# The Economics of Artificial Intelligence Governance — replication materials

Replication and audit materials for **The Economics of Artificial Intelligence Governance: Regulation, Incentives, Market Structure and Accountability — A Systematic Synthesis**.

Version: **v14.6**  
Freeze date: **25 August 2026**

## Data

- `data/EVIDENCE_ROLE_CROSSWALK_v14_6.part01.tsv` through `part08.tsv` — the complete 151-row current evidence-role crosswalk (148 academic works plus 3 separately coded policy/context sources), split only for repository transport. Concatenate the files in numeric order to reconstruct the canonical TSV; `part01` contains the header.
- `data/TENSION_BOUNDARY_MATRIX_v14_6.tsv` — Type I sign/ranking reversals and Type II simultaneous institutional trade-offs, including boundary-evidence status.
- `data/SYNTHESIS_PROPOSITIONS_v14_6.tsv` — synthesis propositions, confidence status, boundaries/provenance, and falsifiers.
- `data/HIGH_CENTRALITY_SEEDS_v14_6.tsv` — citation-chasing seed set used in the review architecture.
- `data/DISPOSITION_AUDIT_v14_6.tsv` — final review-population accounting.
- `data/CREDIBILITY_FRAMEWORK_v14_6.tsv` — credibility dimensions by evidence type.
- `data/ARCHIVAL_REGISTER_INVENTORY_v14_6.tsv` — canonical identities and SHA-256 hashes for the byte-frozen historical row-level registers.

## Documentation

- `docs/SYSTEMATIC_REVIEW_REPORTING_STATEMENT_v14_6.tex` — systematic-review reporting statement.
- `docs/REPLICATION_AND_SOURCE_AUDIT_v14_6.txt` — source and replication audit note.
- `docs/SOURCE_REGISTER_AVAILABILITY_v14_6.txt` — availability and non-reconstruction statement for historical registers.
- `docs/ARCHIVED_REGISTER_ATTACHMENTS_v14_6.txt` — canonical filenames and hashes of the historical row-level registers.
- `DATA_DICTIONARY.md` — descriptions of the machine-readable tables.
- `CITATION.cff` — citation metadata.
- `LICENSE.txt` — CC BY 4.0 terms for repository-authored documentation and audit tables, subject to third-party rights.

## Review populations

The journal-facing synthesis distinguishes the following populations rather than treating them as one denominator:

- 510 deduplicated discovery records;
- 444 working academic candidates after canonicalisation;
- 148 included academic works;
- 296 non-included academic candidates, comprising 145 lower-priority unconfirmed records and 151 source-checked records not performing a distinct final analytical role;
- 3 separately coded policy/context sources;
- 118 proposition-ledger claims;
- 27 fully source-located studies, represented by 69 source-location rows and 51 load-bearing claim IDs.

## Evidential rule

The unit of synthesis is the proposition–design–evidence tuple. Formal results, causal estimates, structural counterfactuals, simulations, qualitative evidence, doctrinal analysis and cross-domain mechanism transfer are not treated as interchangeable evidence. Shared datasets, shocks, benchmarks, model primitives and theoretical lineages are adjusted for dependence before corroboration labels are assigned.

## Historical row-level registers

Six exact historical machine-readable registers are retained as byte-frozen project artifacts. Their canonical filenames and SHA-256 hashes are listed in `data/ARCHIVAL_REGISTER_INVENTORY_v14_6.tsv` and `docs/ARCHIVED_REGISTER_ATTACHMENTS_v14_6.txt`. They are deliberately not recreated from prose because doing so would destroy byte-level provenance. Where the journal permits additional supplementary attachments, the exact frozen files should be supplied separately.

## Replication scope

This article is a systematic economic synthesis, not an analysis of participant-level experimental or administrative microdata. The repository supports review-population accounting, source/evidence classification, boundary-condition synthesis and auditability. It does not claim a new numerical replication exercise.

## Citation

Please cite the associated article and this repository version together when using these materials.

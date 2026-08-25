# Data dictionary

This repository contains review-audit data rather than participant-level or experimental microdata.

## Core tables

### EVIDENCE_ROLE_CROSSWALK_v14_6.tsv
One row per substantively engaged evidential source object. Key fields identify evidence class, provenance, manuscript role, and credibility/transfer limits.

### TENSION_BOUNDARY_MATRIX_v14_6.tsv
One row per synthesis tension. `Type I` denotes genuine sign or policy-ranking reversals over comparable objects. `Type II` denotes simultaneous institutional trade-offs. Boundary-evidence status distinguishes direct evidence, model/institution-imposed boundaries, cross-study inference, and mixed cases.

### SYNTHESIS_PROPOSITIONS_v14_6.tsv
One row per headline synthesis proposition. Fields include confidence status, principal boundary/provenance, and a falsifier or disconfirming observation.

### HIGH_CENTRALITY_SEEDS_v14_6.tsv
Seed set used for backward/forward citation chasing. The associated methods statement defines the admission and stopping logic.

### DISPOSITION_AUDIT_v14_6.tsv
Review-population accounting used to reconcile discovery, candidate, included, non-included and forensic subsets.

### CREDIBILITY_FRAMEWORK_v14_6.tsv
Credibility dimensions used for formal theory, causal/quasi-experimental, observational, structural/calibrated, simulation, qualitative, legal/doctrinal and cross-domain evidence.

### ARCHIVAL_REGISTER_INVENTORY_v14_6.tsv
Canonical filenames, roles and SHA-256 hashes for historical byte-frozen row-level registers.

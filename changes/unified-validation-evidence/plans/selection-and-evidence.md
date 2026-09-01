# Unified validation selection and evidence

Status: approved
Specification: `changes/unified-validation-evidence/specs/selection-and-evidence.toml`
Base: `engine@c00a97a0148e07a9e33ea0002686815e575232f0`

| Obligation | Clauses | Outcome |
| --- | --- | --- |
| PROTOCOL | EVIDENCE-003 | Publish strict Evidence v3 schema and canonical protocol vectors. |
| SELECT | EVIDENCE-001 | Produce a content-bound selection without running validation. |
| MEMBER | EVIDENCE-001, EVIDENCE-004 | Execute selected work plus declared completeness requirements through profiles and adapters. |
| FINAL | EVIDENCE-002 | Execute the complete frozen-batch graph once. |
| CONFORM | EVIDENCE-003 | Validate engine, Template, and PyLM projections against the same protocol identity and vectors. |

The implementation replaces Evidence v2 at the public lifecycle boundary. It
does not retain a fallback reader. Repository-specific scheduling and resource
management remain extension data owned by their adapters.

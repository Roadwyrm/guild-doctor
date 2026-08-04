# Guild Doctor Stage 5 Pass 4 Current-Baseline Readiness Manifest

**Date:** 2026-07-16
**Distribution:** `guild-doctor-scanner-core 0.5.1`
**Status:** Stage 2 and Stage 3 Passes 1-6 complete; Pass 6 live GET-only verification and formal closure complete; Stage 4 Passes 1-4 complete; Stage 4 closure `STAGE4_COMPLETE`; Stage 5 Passes 1-3 complete; Pass 4 current-baseline implementation offline `READY`; secure live capture and replay pending; Stage 5 closure `STAGE5_IN_PROGRESS`; Stage 6 not started

Matching `.sha256` sidecar files are provided for both Stage 4 Pass 4
completion archives, the retained Stage 4 Pass 3 archives, the prior Stage 4
Pass 2 archives, and the retained
Stage 3 closure archives.
The golden fixture checksums are recorded in
`fixtures/stage3_pass6_action_golden.json.sha256` and
`fixtures/stage4_pass1_explanation_golden.json.sha256` and
`fixtures/stage4_pass2_explanation_integration_golden.json.sha256` and
`fixtures/stage4_pass3_explanation_query_golden.json.sha256` and
`fixtures/stage5_pass1_doctor_golden.json.sha256` and
`fixtures/stage5_pass2_doctor_enumeration_golden.json.sha256`.

Stage 5 Pass 3 fixture and archive checksums are recorded in the Pass 3
completion report and matching archive sidecars.

Stage 5 Pass 3 completion archives:

- `Guild_Doctor_Stage5_Pass3_COMPLETE_2026-07-15.zip`
- `Guild_Doctor_Stage5_Pass3_COMPLETE_Release_2026-07-15.zip`

Stage 5 Pass 2 completion archives (retained):

- `Guild_Doctor_Stage5_Pass2_COMPLETE_2026-07-15.zip`
- `Guild_Doctor_Stage5_Pass2_COMPLETE_Release_2026-07-15.zip`

Stage 5 Pass 1 checkpoint archives:

- `Guild_Doctor_Stage5_Pass1_COMPLETE_2026-07-15.zip`
- `Guild_Doctor_Stage5_Pass1_COMPLETE_Release_2026-07-15.zip`

Stage 4 Pass 4 completion archives:

- `Guild_Doctor_Stage4_COMPLETE_2026-07-15.zip`
- `Guild_Doctor_Stage4_COMPLETE_Release_2026-07-15.zip`

Retained Stage 4 Pass 3 archives:

- `Guild_Doctor_Stage4_Pass3_COMPLETE_2026-07-15.zip`
- `Guild_Doctor_Stage4_Pass3_COMPLETE_Release_2026-07-15.zip`

Stage 4 Pass 2 checkpoint archives:

- `Guild_Doctor_Stage4_Pass2_COMPLETE_2026-07-15.zip`
- `Guild_Doctor_Stage4_Pass2_COMPLETE_Release_2026-07-15.zip`

Retained Stage 3 closure archives:

- `Guild_Doctor_Stage3_COMPLETE_2026-07-15.zip`
- `Guild_Doctor_Stage3_COMPLETE_Release_2026-07-15.zip`

## Current identifiers

- Bot name: **Guild Doctor**
- Slash-command group: `/guild-doctor`
- Python package: `guild_doctor_scanner`
- Bot executable: `guild-doctor-bot`
- Environment prefix: `GUILD_DOCTOR_`
- Default database: `data/guild_doctor_snapshots.sqlite3`
- Stage 3 Pass 1 engine: `GUILD-DOCTOR-STAGE3-PASS1-0.1`
- Stage 3 Pass 2 engine: `GUILD-DOCTOR-STAGE3-PASS2-0.1`
- Stage 3 Pass 3 engine: `GUILD-DOCTOR-STAGE3-PASS3-0.1`
- Stage 3 Pass 4 engine: `GUILD-DOCTOR-STAGE3-PASS4-0.1`
- Stage 3 Pass 5 engine: `GUILD-DOCTOR-STAGE3-PASS5-0.1`
- Stage 3 Pass 6 engine: `GUILD-DOCTOR-STAGE3-PASS6-0.1`
- Capability registry: `GUILD-DOCTOR-CAPABILITY-REGISTRY-0.1`
- Thread rules: `GUILD-DOCTOR-THREAD-RULES-0.1`
- Authority rules: `GUILD-DOCTOR-AUTHORITY-RULES-0.1`
- Object preconditions: `GUILD-DOCTOR-OBJECT-PRECONDITIONS-0.1`
- MFA rules: `GUILD-DOCTOR-MFA-RULES-0.1`
- Action rules: `GUILD-DOCTOR-ACTION-RULES-0.1`
- Action golden cases: `GUILD-DOCTOR-ACTION-GOLDEN-0.1`
- Read-only verification support: `GUILD-DOCTOR-LIVE-AUTHORITY-VERIFY-0.1`
- Stage 4 Pass 1 contract: `GUILD-DOCTOR-STAGE4-PASS1-0.1`
- Stage 4 Pass 2 contract: `GUILD-DOCTOR-STAGE4-PASS2-0.1`
- Stage 4 Pass 3 contract: `GUILD-DOCTOR-STAGE4-PASS3-0.1`
- Stage 4 Pass 4 contract: `GUILD-DOCTOR-STAGE4-PASS4-0.1`
- Explanation query contract: `GUILD-DOCTOR-EXPLANATION-QUERY-0.1`
- Explanation orchestration: `GUILD-DOCTOR-EXPLANATION-ORCHESTRATION-0.1`
- Presentation profiles: `GUILD-DOCTOR-PRESENTATION-PROFILES-0.1`
- Explanation schema: `GUILD-DOCTOR-EXPLANATION-SCHEMA-0.1`
- Explanation rules: `GUILD-DOCTOR-EXPLANATION-RULES-0.1`
- Explanation golden cases: `GUILD-DOCTOR-EXPLANATION-GOLDEN-0.1`
- Explanation adapters: `GUILD-DOCTOR-EXPLANATION-ADAPTERS-0.1`
- Explanation integration golden cases: `GUILD-DOCTOR-EXPLANATION-INTEGRATION-GOLDEN-0.1`
- Explanation query golden cases: `GUILD-DOCTOR-EXPLANATION-QUERY-GOLDEN-0.1`
- Explanation runtime: `GUILD-DOCTOR-EXPLANATION-RUNTIME-0.1`
- Explanation batch: `GUILD-DOCTOR-EXPLANATION-BATCH-0.1`
- Explanation runtime golden: `GUILD-DOCTOR-EXPLANATION-RUNTIME-GOLDEN-0.1`
- Stage 4 closure: `GUILD-DOCTOR-STAGE4-CLOSURE-0.1`
- Stage 5 Pass 1 contract: `GUILD-DOCTOR-STAGE5-PASS1-0.1`
- Doctor query contract: `GUILD-DOCTOR-DOCTOR-QUERY-0.1`
- Doctor case contract: `GUILD-DOCTOR-DOCTOR-CASE-0.1`
- Doctor rules contract: `GUILD-DOCTOR-DOCTOR-RULES-0.1`
- Doctor golden cases: `GUILD-DOCTOR-DOCTOR-GOLDEN-0.1`
- Stage 5 Pass 2 contract: `GUILD-DOCTOR-STAGE5-PASS2-0.1`
- Enumeration query contract: `GUILD-DOCTOR-ENUMERATION-QUERY-0.1`
- Enumeration case contract: `GUILD-DOCTOR-ENUMERATION-CASE-0.1`
- Enumeration rules: `GUILD-DOCTOR-ENUMERATION-RULES-0.1`
- Enumeration golden cases: `GUILD-DOCTOR-ENUMERATION-GOLDEN-0.1`
- Stage 5 Pass 3 contract: `GUILD-DOCTOR-STAGE5-PASS3-0.1`
- Source-location query contract: `GUILD-DOCTOR-SOURCE-LOCATION-QUERY-0.1`
- Source-location case contract: `GUILD-DOCTOR-SOURCE-LOCATION-CASE-0.1`
- Role-comparison query contract: `GUILD-DOCTOR-ROLE-COMPARISON-QUERY-0.1`
- Role-comparison case contract: `GUILD-DOCTOR-ROLE-COMPARISON-CASE-0.1`
- Stage 5 Pass 3 rules: `GUILD-DOCTOR-STAGE5-PASS3-RULES-0.1`
- Stage 5 Pass 3 golden cases: `GUILD-DOCTOR-STAGE5-PASS3-GOLDEN-0.1`
- Permission definition: `DISCORD-PERM-2026-07-13`
- Closure assessment: `GUILD-DOCTOR-STAGE3-CLOSURE-0.1`

## Included

- Read-only guild, role, channel, and active-thread scanner
- Targeted and temporary exhaustive member acquisition
- Immutable SQLite snapshot persistence
- Owner-only status, scan, scan-health, and server-summary commands
- Disposable-guild Pass 5 verification harness
- Deterministic Stage 3 Pass 1 guild-level permission engine
- Deterministic Stage 3 Pass 2 raw category/channel overwrite engine
- Deterministic Stage 3 Pass 3 effective capability expansion and registry
- Deterministic Stage 3 Pass 4 thread relationship and capability resolution
- Deterministic Stage 3 Pass 5 authority components and object preconditions
- Deterministic Stage 3 Pass 6 action-rule registry and pre-execution orchestrator
- Read-only verification support over already acquired Pass 3-5 results
- Bounded GET-only Pass 6 live verifier and redacted evidence writer
- `stage3-pass6-scenarios.json`, secure Windows runner, live setup checklist, and closure reassessment CLI
- 35 external golden cases and 144 focused Pass 6 tests
- 10 closure-assessment regression tests; 65 focused Stage 4 Pass 1 tests; 52 focused Stage 4 Pass 2 tests; 115 focused and golden Stage 4 Pass 3 tests
- 12 deterministic Stage 4 Pass 1 explanation golden cases
- 22 deterministic Stage 4 Pass 2 adapter/integration golden cases
- 35 deterministic Stage 4 Pass 3 query/orchestration golden cases
- 30 deterministic Stage 4 Pass 4 runtime golden cases
- 36 deterministic Stage 5 Pass 1 Doctor golden cases
- 50 deterministic Stage 5 Pass 2 enumeration golden cases
- 70 deterministic Stage 5 Pass 3 source-location and role-comparison golden cases
- 1077 pytest tests and 458 unittest tests passed; details are recorded in `TEST_RESULTS.txt`
- 23 focused Stage 5 Pass 1 query/case/engine tests
- 52 focused Stage 5 Pass 2 query/population/aggregation/engine tests
- 121 focused and golden Stage 5 Pass 3 query/source/projection/comparison tests
- Windows installation and startup scripts
- Guild Doctor avatar
- Pass 5 live evidence bundle
- Retained Stage 3 baseline: 636 pytest tests and 458 unittest discovery tests

## Live evidence

- `pass5-evidence/integration_report.json`
- `pass5-evidence/live_snapshot.json`
- `pass5-evidence/partial_failure_health.json`
- `pass5-evidence/stage3_fixture.json`

Pass 6 live evidence is present under `stage3-pass6-evidence`:

- `authority_verification_report.json`
- `authority_live_snapshot.json`
- `repeated_authority_live_snapshot.json`
- `action_results.json`
- `acquisition_health.json`
- `scenario_manifest_redacted.json`
- `transport_audit.json`
- `stage3_closure_assessment.json`
- `verification_backlog.json`

Stage 4 explanation fixtures:

- `fixtures/stage4_pass1_explanation_golden.json`
- `fixtures/stage4_pass2_explanation_integration_golden.json`
- `fixtures/stage4_pass3_explanation_query_golden.json`
- `fixtures/stage4_pass3_explanation_query_golden.json.sha256`
- `fixtures/stage4_pass4_explanation_runtime_golden.json`
- `fixtures/stage4_pass4_explanation_runtime_golden.json.sha256`

Stage 4 Pass 4 evidence is present under `stage4-pass4-evidence`:

- `runtime_verification_report.json`
- `live_derived_explanations.json`
- `cli_single_query_report.json`
- `cli_batch_report.json`
- `canonical_environment_report.json`
- `clean_wheel_report.json`
- `console_compatibility_report.json`
- `evidence_integrity_report.json`
- `stage4_closure_assessment.json`
- `verification_backlog.json`
- `runtime_golden_results.json`
- `runtime_output_manifest.json`

Stage 5 Pass 1 local contract and golden evidence:

- `guild_doctor_scanner/doctor_query.py`
- `guild_doctor_scanner/doctor_rules.py`
- `guild_doctor_scanner/doctor_case.py`
- `guild_doctor_scanner/doctor_engine.py`
- `fixtures/stage5_pass1_doctor_golden.json`

Stage 5 Pass 2 local contract and golden evidence is present under
`stage5-pass2-evidence`:

- `enumeration_verification_report.json`
- `golden_results.json`
- `route_coverage_report.json`
- `population_completeness_report.json`
- `server_wide_wording_report.json`
- `live_derived_enumeration_report.json`
- `determinism_report.json`
- `frozen_interface_report.json`
- `read_only_audit_report.json`
- `evidence_integrity_report.json`
- `clean_wheel_report.json`
- `verification_backlog.json`
- `artifact_manifest.json`

The Pass 2 fixture is `fixtures/stage5_pass2_doctor_enumeration_golden.json`.

Stage 5 Pass 3 local contract and golden evidence is present under
`stage5-pass3-evidence`:

- `pass3_verification_report.json`
- `source_location_golden_results.json`
- `role_comparison_golden_results.json`
- `source_type_coverage_report.json`
- `role_projection_report.json`
- `capability_matrix_report.json`
- `action_comparison_report.json`
- `source_ordering_report.json`
- `comparison_determinism_report.json`
- `frozen_interface_report.json`
- `no_duplicated_logic_report.json`
- `wording_safety_report.json`
- `read_only_audit_report.json`
- `evidence_integrity_report.json`
- `live_derived_comparison_report.json`
- `verification_backlog.json`
- `artifact_manifest.json`

Pass 3 evidence is deterministic local fixture evidence, not a live Discord
result. It records zero Discord requests and zero Discord writes.

The Stage 3 closure assessment is `STAGE3_COMPLETE` with zero concrete
blockers. The Stage 4 closure assessment is `STAGE4_COMPLETE` with zero
concrete blockers.

## Stage boundary

Stage 2 - Server Scanner and Normalized Model is complete. Stage 3 Passes 1-6
implementation and Pass 6 live structure verification are complete. Pass 6
remains a pre-execution, GET-only model boundary: no endpoint success, human
MFA, voice state, post-acquisition state change, or write operation is claimed.
No useful live active thread was present; the accepted thread limitation and
synthetic/documented local coverage are recorded in the closure assessment.
Stage 4 is **COMPLETE** with Passes 1-4 complete and formal closure
`STAGE4_COMPLETE` with zero concrete blockers. The Pass 4 runtime and CLI are
local-only and invoke only the public Pass 3 orchestrator. Live-derived
verification reads retained Stage 3 evidence, produces 18 presentations, and
records no network contact, Discord writes, or AI invocation. Stage 5 Passes
1-3 are complete. Stage 5 Pass 4 is implemented as a local-only checkpoint;
formal Stage 5 closure is `STAGE5_IN_PROGRESS` because the sanitized frozen
evidence cannot reproduce historical result state and primary reason without
the redacted inputs. Stage 3 Pass 7 and Stage 6 have not started. No Discord
write operations are included.

Stage 3 Pass 4 uses live-derived parent evidence plus explicitly synthetic thread and
membership records because the live fixture has no useful live threads. The
labels are `LIVE_DERIVED_PARENT`, `SYNTHETIC_THREAD`,
`SYNTHETIC_MEMBERSHIP`, `DOCUMENTED_EXPECTATION`, and `NEEDS_LIVE_TEST`.

Pass 6 uses `DOCUMENTED_EXPECTATION`, `SYNTHETIC_ORCHESTRATION`,
`LIVE_DERIVED_INPUT`, and `NEEDS_LIVE_TEST`. Its deterministic result is a
pre-execution model only; no operation was attempted and no live transport
success is claimed.

Stage 4 Pass 1 uses frozen Stage 3 result and trace evidence only. Pass 2 adds
six immutable representation adapters and a deterministic integration boundary
that delegates wording to the Pass 1 renderer. The adapters preserve source
objects, trace order, exact source contracts, provenance, evidence limitations,
and pre-execution controls; they never invoke Stage 3 calculation or a Discord
operation. Pass 3 adds only pure query selection, profile selection,
presentation disclosure, safe formatting, truncation, and fingerprints. Pass 4
adds only the local runtime, CLI, batch contract, offline live-derived
verification, atomic local outputs, and closure gates. It does not alter any
frozen contract or schema version.

Stage 5 Pass 1 is a local, command-free Doctor layer. It validates one
structured subject/target query, assembles explicit snapshot/member evidence,
delegates calculation to frozen Stage 3 public engines, delegates explanation
to the frozen Stage 4 public orchestrator, and emits a deterministic
`DoctorCase`. It does not enumerate members, parse natural language, contact
Discord, invoke AI, recommend repairs, persist cases, register commands, or
perform writes. Stage 5 Passes 2-3 are complete and Stage 6 remains unstarted.

Stage 5 Pass 2 is a local, command-free finite-population layer. It evaluates
each selected candidate through only the public Pass 1
`execute_doctor_query` interface, aggregates ALLOWED, DENIED, INEFFECTIVE,
UNKNOWN, NOT_APPLICABLE, and UNSUPPORTED buckets, and marks partial or
incomplete populations honestly. It performs no Discord request, persistence,
command registration, recommendation, risk scoring, or write. Stage 5 Pass 3
is complete as a local source-location and hypothetical role-comparison layer;
Stage 5 Pass 4 adds local structured workflow plans for WHY, enumeration,
source-location, and role-comparison queries; a deterministic guided selector;
the `guild-doctor-doctor` direct, batch, validation, verification, and closure
CLI; safe local output; and a clean installed-wheel gate. It routes exclusively
to frozen Pass 1-3 interfaces and Stage 4 presentation. Canonical tests passed
1202 pytest and 458 unittest tests; the local clean-wheel guided, direct, batch,
and closure CLI smoke paths passed with no network, Discord request, or write.

Formal Stage 5 closure is intentionally `STAGE5_IN_PROGRESS`. Public frozen
live-derived evidence protects member/context data by redaction, so local
re-execution cannot prove preservation of the recorded historical result state
or primary reason. Those concrete blockers are retained in
`stage5-pass4-evidence/stage5_closure_assessment.json`; this is an
implementation checkpoint, not a Stage 5-complete release. Stage 6 remains
unstarted.

The only new archive is the explicitly non-completion checkpoint
`Guild_Doctor_Stage5_Pass4_IMPLEMENTATION_CHECKPOINT_2026-07-16.zip` with its
matching SHA-256 sidecar. No archive claims Stage 5 completion.

# Guild Doctor Scanner Core - Stage 5 Pass 4 Current-Baseline Readiness Checkpoint

This package contains completed Stage 2, Stage 3 Passes 1-6, Stage 4 Passes 1-4, and Stage 5. Stage 5 closure is `STAGE5_COMPLETE`: three privacy-safe current-baseline capsules replay exactly without network access or Discord writes. Historical evidence remains permanently `NOT_REPLAYABLE_MISSING_RETAINED_INPUT`; the current baseline neither reconstructs nor supersedes historical state. Stage 6 is not started.

## Naming

This package is branded and operated as **Guild Doctor**. The bot command group is `/guild-doctor`, executable commands begin with `guild-doctor-`, and environment variables begin with `GUILD_DOCTOR_`.


## Versions

- Package: `0.5.1`
- Scanner contract: `GUILD-DOCTOR-SCANNER-0.5`
- Snapshot schema: `GUILD-DOCTOR-SNAPSHOT-0.1`
- Integration contract: `GUILD-DOCTOR-INTEGRATION-0.1`
- Stage 3 fixture format: `GUILD-DOCTOR-STAGE3-FIXTURE-0.1`
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
- Stage 4 Pass 1 contract: `GUILD-DOCTOR-STAGE4-PASS1-0.1`
- Stage 4 Pass 2 contract: `GUILD-DOCTOR-STAGE4-PASS2-0.1`
- Stage 4 Pass 3 contract: `GUILD-DOCTOR-STAGE4-PASS3-0.1`
- Stage 4 Pass 4 contract: `GUILD-DOCTOR-STAGE4-PASS4-0.1`
- Explanation query contract: `GUILD-DOCTOR-EXPLANATION-QUERY-0.1`
- Explanation orchestration: `GUILD-DOCTOR-EXPLANATION-ORCHESTRATION-0.1`
- Presentation profiles: `GUILD-DOCTOR-PRESENTATION-PROFILES-0.1`
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
- Stage 5 Pass 4 contract: `GUILD-DOCTOR-STAGE5-PASS4-0.1`
- Doctor workflow: `GUILD-DOCTOR-DOCTOR-WORKFLOW-0.1`
- Guided selector: `GUILD-DOCTOR-DOCTOR-GUIDED-SELECTOR-0.1`
- Doctor CLI: `GUILD-DOCTOR-DOCTOR-CLI-0.1`
- Doctor runtime golden: `GUILD-DOCTOR-DOCTOR-RUNTIME-GOLDEN-0.1`
- Stage 5 closure: `GUILD-DOCTOR-STAGE5-CLOSURE-0.1`
- Retained input: `GUILD-DOCTOR-STAGE5-RETAINED-INPUT-0.1`
- Privacy-safe replay: `GUILD-DOCTOR-PRIVACY-SAFE-REPLAY-0.1`
- Replay capsule: `GUILD-DOCTOR-REPLAY-CAPSULE-0.1`
- Current baseline: `GUILD-DOCTOR-STAGE5-CURRENT-BASELINE-0.1`
- GET-only acquisition: `GUILD-DOCTOR-GET-ONLY-ACQUISITION-0.1`
- Privacy-safe baseline: `GUILD-DOCTOR-PRIVACY-SAFE-BASELINE-0.1`
- Current baseline replay: `GUILD-DOCTOR-CURRENT-BASELINE-REPLAY-0.1`
- Explanation schema: `GUILD-DOCTOR-EXPLANATION-SCHEMA-0.1`
- Explanation rules: `GUILD-DOCTOR-EXPLANATION-RULES-0.1`
- Explanation golden cases: `GUILD-DOCTOR-EXPLANATION-GOLDEN-0.1`
- Explanation adapters: `GUILD-DOCTOR-EXPLANATION-ADAPTERS-0.1`
- Explanation integration golden cases: `GUILD-DOCTOR-EXPLANATION-INTEGRATION-GOLDEN-0.1`
- Explanation query golden cases: `GUILD-DOCTOR-EXPLANATION-QUERY-GOLDEN-0.1`
- Read-only verification support: `GUILD-DOCTOR-LIVE-AUTHORITY-VERIFY-0.1`
- Live report format: `GUILD-DOCTOR-STAGE3-PASS6-LIVE-REPORT-0.1`
- Closure assessment: `GUILD-DOCTOR-STAGE3-CLOSURE-0.1`
- Scenario manifest: `GUILD-DOCTOR-STAGE3-PASS6-SCENARIOS-0.1`
- Permission definition: `DISCORD-PERM-2026-07-13`
- Runtime library: `discord.py==2.7.1`
- Discord API: `v10`

## Stage 2 status

**COMPLETE** — the live Pass 5 report is at `pass5-evidence/integration_report.json`.

Verified live:

- Guild, roles, channels, and active threads: `COMPLETE`
- Repeated structural fingerprint: `0788ea289df37f050df3bd5cd800212b3cd1ce14713a056d9500e6adaa676295`
- Owner authorization: `PASS`
- Non-owner denial: `PASS`
- Controlled active-thread failure: `PASS`, with `records=null`
- Anonymized fixture SHA-256: `644f246c5ca34718a5051544fc72af5f2d85a4a5131c23129c81496310714542`

## Pass 5 capabilities

- Two consecutive live structural scans through REST GET endpoints
- Raw-acquisition-to-normalized-snapshot provenance comparison
- Structural drift comparison between scans
- Owner and non-owner authorization-policy verification using the live guild owner ID
- Controlled collection-failure injection without calling Discord write endpoints
- Privacy-minimized, anonymized Stage 3 fixture export
- Static integration-path mutation audit
- Explicit disposable-guild confirmation gate

## Stage 3 Pass 1 status

**COMPLETE** - `guild_doctor_scanner/permission_engine.py` provides a pure,
deterministic guild-level permission calculation. It evaluates the @everyone
role, assigned-role union, owner bypass, Administrator bypass, known and
unknown permission bits, missing or invalid references, explicit input health,
and a stable trace. It does not resolve channel overwrites, threads, timeouts,
capability dependencies, actions, commands, or Discord writes.

The engine consumes the frozen scanner/snapshot data, the frozen permission
definition `DISCORD-PERM-2026-07-13`, and either the frozen snapshot schema or
Stage 3 fixture version. Stage 3 overall status is **COMPLETE**. Passes 1-6
are complete. Pass 6 live structure verification and formal closure assessment
passed; Stage 3 Pass 7 has not started.

## Stage 3 Pass 2 status

**COMPLETE** - `guild_doctor_scanner/permission_overwrite_engine.py` resolves
raw category and guild-channel permissions using the selected context's own
overwrite set. It follows Discord's @everyone, combined-role, and member
overwrite order, preserves unknown bits, records structural sync metadata,
and never layers category overwrites onto a child channel. Owner and
Administrator bypasses preserve the Pass 1 raw guild result.

Threads, thread inheritance, timeouts, hierarchy, capabilities, actions,
commands, explanations, audits, charts, persistence changes, and Discord
writes remain outside this pass. Pass 4 is the separate thread-resolution
boundary described below.

## Stage 3 Pass 3 status

**COMPLETE** - `guild_doctor_scanner/capability_registry.py` defines the
versioned known-permission registry, and
`guild_doctor_scanner/capability_engine.py` expands a completed Pass 2 result
into deterministic `ALLOWED`, `DENIED`, `INEFFECTIVE`, `UNKNOWN`,
`NOT_APPLICABLE`, and category `POLICY_ONLY` records. It preserves raw guild
and context bitfields, known flags, unknown bits, bypass source, timeout
state, dependency uncertainties, verification status, and an ordered trace.

The pass covers `TEXT`, `ANNOUNCEMENT`, `VOICE`, `STAGE`, `FORUM`, and
`MEDIA`. Categories are policy-only. Thread contexts are resolved only by Pass
4. Hierarchy, target-role, MFA,
object-precondition, action-result, command, persistence, and Discord-write
behavior remain out of scope.

## Stage 3 Pass 4 status

**COMPLETE** - `guild_doctor_scanner/thread_engine.py` consumes completed Pass 2
parent evidence and the Pass 3 parent capability result. It resolves public,
private, and announcement thread relationships; inherited `VIEW_CHANNEL`,
`READ_MESSAGE_HISTORY`, `MANAGE_THREADS`, and
`SEND_MESSAGES_IN_THREADS`; private membership; timeout-aware behavior; and
archived/locked state. `SEND_MESSAGES` is never used as a thread-send
substitute. The resolver preserves parent raw decimal/hex and unknown bits,
emits stable records and trace stages, predicts auto-unarchive only, and never
performs a Discord write.

Supported parent relationships are public threads on `TEXT`, `FORUM`, or
`MEDIA`; private threads on `TEXT`; and announcement threads on
`ANNOUNCEMENT`. Missing or incomplete membership, archive, lock, parent, or
capability evidence remains `UNKNOWN`/incomplete.

Official sources reviewed on 2026-07-14:

- https://docs.discord.com/developers/topics/permissions
- https://docs.discord.com/developers/topics/threads
- https://docs.discord.com/developers/resources/channel

The live-derived fixture contains no useful live threads. Pass 4 local
coverage uses the live-derived parent and explicitly labeled synthetic thread
and membership records: `LIVE_DERIVED_PARENT`, `SYNTHETIC_THREAD`,
`SYNTHETIC_MEMBERSHIP`, `DOCUMENTED_EXPECTATION`, and `NEEDS_LIVE_TEST`.
Synthetic behavior is not claimed as live-tested. Pass 5 is complete as a pure
local authority-analysis boundary; its synthetic actor, target, operation,
MFA, hierarchy, managed-object, voice, and overwrite cases are not claims of
live Discord coverage. Pass 6 live verification covered the real actor/member,
role, and text-channel structure through GET-only acquisition. No useful live
active thread was present, so synthetic/documented thread coverage remains an
accepted read-only limitation.

## Stage 3 Pass 5 status

**COMPLETE** under `GUILD-DOCTOR-STAGE3-PASS5-0.1`. The pure Pass 5 layer
keeps capability permission, target authority, strict role hierarchy, MFA,
permission subsets, managed-object restrictions, and operation preconditions
as separate records. It consumes explicit Pass 1-4 evidence and performs no
network, persistence, command, token, or Discord write operation. It does not
produce a generic operation conclusion.

Pass 5 adds the versioned `GUILD-DOCTOR-AUTHORITY-RULES-0.1`,
`GUILD-DOCTOR-OBJECT-PRECONDITIONS-0.1`, and separate
`GUILD-DOCTOR-MFA-RULES-0.1` registries. The MFA registry is additive because
the frozen `DISCORD-PERM-2026-07-13` definition contains no MFA asterisk
metadata. The reviewed current single-asterisk set includes
`ADMINISTRATOR`, `BAN_MEMBERS`, `KICK_MEMBERS`, `MANAGE_CHANNELS`,
`MANAGE_GUILD`, `MANAGE_GUILD_EXPRESSIONS`, `MANAGE_MESSAGES`,
`MANAGE_ROLES`, `MANAGE_THREADS`, `MANAGE_WEBHOOKS`, and
`VIEW_CREATOR_MONETIZATION_ANALYTICS`. `MODERATE_MEMBERS` remains outside
that set because the official table marks it with the timeout-specific
double-asterisk note.

## Stage 3 Pass 6 status

**COMPLETE** under
`GUILD-DOCTOR-STAGE3-PASS6-0.1`. The immutable
`GUILD-DOCTOR-ACTION-RULES-0.1` registry covers 32 actions already modeled by
Pass 3, Pass 4, or Pass 5. The pure orchestrator combines versioned,
health-checked evidence using explicit precedence: malformed input and
contract/identity contradictions remain `UNKNOWN`; definitive required
blockers produce `DENIED`; complete satisfied evidence produces `ALLOWED`;
legitimate registry mismatches produce `NOT_APPLICABLE`; and an unregistered
operation produces `UNSUPPORTED`.

Every result is marked `decision_basis=PRE_EXECUTION_MODEL`,
`execution_attempted=false`, and `execution_guarantee=false`. The action golden
fixture contains 35 deterministic cases with evidence classifications. The
read-only verification support accepts already acquired Pass 3-5 results and
does not invoke a Discord operation. The live verifier acquired only
manifest-authorized guild, role, channel, thread, and member records through
bounded GET operations, repeated the acquisition, and fed the pure Pass 1-6
engines. The formal closure assessment is `STAGE3_COMPLETE` with zero concrete
blockers. The modeled results remain pre-execution only: no endpoint success,
MFA, voice state, post-acquisition state change, or write operation is claimed.
Pass 7 has not started.

## Stage 4 Pass 1 status

**COMPLETE** under `GUILD-DOCTOR-STAGE4-PASS1-0.1`. The pure explanation layer
consumes frozen Stage 3 result records and traces without invoking a Stage 3
evaluator. It preserves the authoritative result state, raw-versus-effective
distinctions, component separation, source rule IDs, uncertainty, bypass
treatment, pre-execution limitations, and source provenance. It renders
`SIMPLE`, `DETAILED`, and `TECHNICAL` modes for guild permission, context
permission, capability, thread, authority, and action results.

The explanation schema is `GUILD-DOCTOR-EXPLANATION-SCHEMA-0.1`, the immutable
rule registry is `GUILD-DOCTOR-EXPLANATION-RULES-0.1`, and the 12-case golden
fixture is `fixtures/stage4_pass1_explanation_golden.json` under
`GUILD-DOCTOR-EXPLANATION-GOLDEN-0.1`. The renderer is deterministic,
downstream-only, label-safe, token-redacting, and has no Discord, network,
persistence, command, or AI dependency.

## Stage 4 Pass 2 status

**COMPLETE** under `GUILD-DOCTOR-STAGE4-PASS2-0.1`. The immutable adapter
registry maps all six frozen Stage 3 result families to Pass 1 requests without
importing or invoking a Stage 3 evaluator. The adapters preserve source result
and trace order, validate exact contracts, decimal snowflake identities,
versioned registries, completeness, evidence classifications, verification
statuses, action pre-execution controls, and historical-versus-authoritative
closure precedence. Missing or contradictory material trace evidence remains
incomplete or is reported as an adapter error; no values are fabricated.

`explanation_integration.py` composes a valid adapter result with the existing
Pass 1 renderer only. It records adapter, source-result, source-trace, and
explanation fingerprints; keeps raw result objects unchanged; redacts
credential-shaped fields from diagnostic serialization; and never contacts
Discord, persists data, invokes AI, or performs a Discord operation. The
22-case fixture is `fixtures/stage4_pass2_explanation_integration_golden.json`
under `GUILD-DOCTOR-EXPLANATION-INTEGRATION-GOLDEN-0.1`.

## Stage 4 Pass 3 status

**COMPLETE** under `GUILD-DOCTOR-STAGE4-PASS3-0.1`. The immutable query
registry maps six explicit query types to the six frozen Stage 3 result
families. The six immutable presentation profiles cover simple cards,
detailed reports, technical records, Discord-safe simple and detailed
Markdown, and complete machine JSON. The pure orchestrator composes the
existing Pass 2 adapter and Pass 1 renderer, then applies presentation-only
disclosure, mention neutralization, Markdown escaping, section selection,
bounded truncation, deterministic fingerprints, and safety status reporting.

The Pass 3 query contract is `GUILD-DOCTOR-EXPLANATION-QUERY-0.1`; the
orchestration contract is `GUILD-DOCTOR-EXPLANATION-ORCHESTRATION-0.1`; and
the profile registry is `GUILD-DOCTOR-PRESENTATION-PROFILES-0.1`. The
35-case fixture is
`fixtures/stage4_pass3_explanation_query_golden.json` under
`GUILD-DOCTOR-EXPLANATION-QUERY-GOLDEN-0.1`. Pass 3 is representation-only:
it does not calculate, contact Discord, persist data, invoke AI, recommend
configuration changes, perform audits, generate charts, or perform Discord
writes. All result state, primary reason, uncertainty, pre-execution
disclaimer, closure precedence, and source provenance remain unchanged.

Stage 4 Pass 4 is **COMPLETE** under `GUILD-DOCTOR-STAGE4-PASS4-0.1`. The
local runtime calls only the public Pass 3 orchestrator, supports single and
batch rendering, validates safe local paths, writes atomic UTF-8 outputs, and
returns deterministic exit codes. The runtime has no Discord, Gateway, HTTP,
persistence, command, token, or AI dependency. Stage 5 Passes 1-3 are
complete; Stage 5 Pass 4 is implemented as a local-only workflow/runtime
checkpoint and formal Stage 5 closure remains `STAGE5_IN_PROGRESS` pending the
documented frozen-evidence preservation blocker. Stage 3 Pass 7 has not
started.

## Stage 4 Pass 4 status

**COMPLETE** with formal closure `GUILD-DOCTOR-STAGE4-CLOSURE-0.1` and
decision `STAGE4_COMPLETE`.

`guild_doctor_scanner.explanation_runtime` validates JSON queries, rejects
credential-shaped input, invokes only
`guild_doctor_scanner.explanation_orchestrator.orchestrate_explanation`, and
preserves frozen result state, primary reason, uncertainty, disclaimers, and
provenance. `guild_doctor_scanner.explanation_cli` provides `render`, `batch`,
`validate`, `verify`, and `contract` modes with flushed progress, atomic local
output, no implicit overwrite, safe extensions, and stable exit codes.

Offline live-derived verification reads retained Stage 3 Pass 6 evidence and
the private scenario manifest without contacting Discord. It produces six
profiles for each of three modeled action scenarios: 18 presentations total.
Hashed/null identity fields are projected only in memory to satisfy the frozen
adapter shape; source evidence is unchanged and diagnostic IDs are redacted or
hashed. The output is `stage4-pass4-evidence/live_derived_explanations.json`.

The formal evidence directory is `stage4-pass4-evidence`. It contains runtime,
CLI, golden, canonical-environment, clean-wheel, console, evidence-integrity,
output-manifest, closure, and backlog reports. Closure records zero concrete
blockers, zero Discord write requests, no network contact, no AI invocation,
and exactly 25 Project Sources Markdown files.

## Stage 5 Pass 1 status

**COMPLETE** under `GUILD-DOCTOR-STAGE5-PASS1-0.1`; Stage 5 overall is
**IN PROGRESS**. `doctor_query.py` validates one explicit subject and one
registered capability or action target. `doctor_engine.py` assembles supplied
snapshot/member evidence, delegates to the frozen Stage 3 Passes 1-6 public
interfaces, and sends the selected result through the frozen Stage 4 public
orchestrator. `doctor_rules.py` performs only premise alignment, evidence
ordering, and source-location labeling; it does not recalculate permissions.
`doctor_case.py` returns deterministic actual-result, diagnostic-answer,
explanation, provenance, and integrity sections.

The golden fixture is
`fixtures/stage5_pass1_doctor_golden.json` under
`GUILD-DOCTOR-DOCTOR-GOLDEN-0.1`. The official Discord permissions,
application-command, and interaction-receiving documentation was reviewed on
2026-07-15. Stage 5 Pass 1 is local and command-free: it performs no Discord
acquisition, Gateway connection, persistence query, AI call, command
registration, or Discord write. Passes 2 and 3 are now complete and Pass 4 is
the next bounded scope.

## Stage 5 Pass 2 status

**COMPLETE** under `GUILD-DOCTOR-STAGE5-PASS2-0.1`; Stage 5 overall remains
**IN PROGRESS**.

The additive enumeration layer accepts one immutable finite population and one
registered capability or fixed-target action. It supports `WHO_CAN`,
`WHO_CANNOT`, `WHO_UNKNOWN`, and `ENUMERATE_ACTUAL_RESULTS`, normalizes
explicit candidates or snapshot members, records every exclusion/duplicate/
invalid disposition, and routes every evaluated candidate through the frozen
Stage 5 Pass 1 `execute_doctor_query` interface. It does not invoke Stage 3 or
Stage 4 engines directly and does not duplicate permission or explanation
logic.

Population coverage, candidate completeness, and diagnostic-result completeness
remain separate. Complete-population wording is emitted only when complete
coverage, complete collection health, agreeing expected/retrieved counts, and
zero unaccounted candidate dispositions are proven. Partial and explicit sets
use bounded wording. `UNKNOWN`, `INEFFECTIVE`, `NOT_APPLICABLE`, and
`UNSUPPORTED` remain separate result buckets; action results retain the
`PRE_EXECUTION_MODEL` disclaimer.

The golden fixture is
`fixtures/stage5_pass2_doctor_enumeration_golden.json` with 50 cases. Pass 2
is local, deterministic, read-only, command-free, persistence-free, and AI-free.
The evidence bundle is `stage5-pass2-evidence/`; it records the local
verification, golden, route, population, wording, determinism, frozen
interface, read-only, clean-wheel, integrity, backlog, and live-derived
limitation reports. No live Pass 2 execution is claimed.

## Stage 5 Pass 3 status

**COMPLETE** under `GUILD-DOCTOR-STAGE5-PASS3-0.1`; Stage 5 overall remains
**IN PROGRESS**.

Pass 3 adds two pure deterministic diagnostic workflows. Source-location
queries (`FIND_CONTROLLING_SOURCE`, `TRACE_SOURCE_CHAIN`,
`LIST_MATERIAL_SOURCES`, and `EXPLAIN_SOURCE_OBJECT`) wrap the frozen Pass 1
`execute_doctor_query` interface, preserve each `DoctorCase`, and extract
structured source records from retained traces and result records. Role
comparison supports raw stored role permissions, one fixed-context capability,
finite capability sets, fixed-target pre-execution action authority, and
explicit difference enumeration. Role subjects are hypothetical role-set
projections, never real members; member overwrites, timeout, thread membership,
human MFA, voice state, ownership, hierarchy, and object-state assumptions are
stated explicitly and remain `UNKNOWN` when material evidence is absent.

Pass 3 never contacts Discord, writes persistence, registers commands, invokes
AI, enumerates members, ranks roles, recommends changes, or performs repairs.
Raw role permissions are never described as effective member permissions.
Source-location output is descriptive and records controlling, contributing,
ineffective, bypassed, unknown, missing, and accepted-limitation evidence
without remediation advice. Capability-set matrices are finite and
deterministic; action comparison retains `PRE_EXECUTION_MODEL`,
`execution_attempted=false`, and `execution_guarantee=false`.

The golden fixture is
`fixtures/stage5_pass3_doctor_comparison_golden.json` with 70 cases. The
offline evidence bundle is `stage5-pass3-evidence/` with 17 JSON reports,
including source-location, role-comparison, projection, matrix, action,
determinism, frozen-interface, read-only, integrity, and backlog reports. The
bundle records `discord_requests=0` and `discord_writes=0`; it is not a live
Discord result.

## Live verification command

Use only with a disposable test guild. Pass 5 remains available through the
existing command. Pass 6 uses the secure Windows runner below.

PowerShell:

```powershell
Set-Location -LiteralPath "C:\GuildDoctor"
& "C:\GuildDoctor\RUN_GUILD_DOCTOR_STAGE3_PASS6_LIVE.ps1" -GuildId GUILD_ID -ScenarioManifest "C:\GuildDoctor\stage3-pass6-scenarios.json" -OutputDirectory "C:\GuildDoctor\stage3-pass6-evidence"
```

The runner prompts securely for the token and confirmation. The completed
Pass 6 scenario manifest and live evidence are retained in this checkout.

Linux/macOS:

```bash
export GUILD_DOCTOR_DISCORD_TOKEN="..."
export GUILD_DOCTOR_DISPOSABLE_GUILD_CONFIRMED=1
guild-doctor-integration-verify GUILD_ID --output-dir pass5-evidence
```

Optional checks:

```bash
guild-doctor-integration-verify GUILD_ID \
  --output-dir pass5-evidence \
  --expected-owner-id OWNER_ID \
  --non-owner-id NON_OWNER_ID \
  --partial-failure-resource active_threads
```

The command writes these evidence files:

- `integration_report.json`
- `live_snapshot.json`
- `partial_failure_health.json`
- `stage3_fixture.json`
- `fixtures/stage3_pass6_action_golden.json`

Pass 6 evidence is written only under `stage3-pass6-evidence` and includes the
authority report, both redacted snapshots, action results, acquisition health,
scenario manifest, verification backlog, transport audit, and closure
assessment. The closure files are `stage3_closure_assessment.json` and
`verification_backlog.json`.

## Safety boundary

The verifier logs in over Discord's HTTP API and does not open a Gateway connection. It uses the pinned GET-only transport used by the live acquisition paths; every login and read is bounded. It never exposes a generic request surface or calls a Discord write endpoint. Pass 4 itself is pure and does not access Discord. Human MFA and voice state are never fabricated when the reviewed reads cannot observe them. No message content or member profiles are included in the Stage 3 fixture.

## Evidence and test status

- Live report: `pass5-evidence/integration_report.json`
- Live snapshot: `pass5-evidence/live_snapshot.json`
- Partial-failure health: `pass5-evidence/partial_failure_health.json`
- Anonymized fixture: `pass5-evidence/stage3_fixture.json`
- Stage 5 Pass 2 local evidence: `stage5-pass2-evidence/`
- Stage 5 Pass 3 local evidence: `stage5-pass3-evidence/`
- Stage 5 Pass 4 retained-input assessment: `stage5-pass4-evidence/retained_input_capability_assessment.json`
- Stage 5 Pass 4 replay gap report: `stage5-pass4-evidence/retained_input_gap_report.json`
- Stage 5 current-baseline readiness evidence: `stage5-current-baseline-evidence/`
- Automated suite before Pass 5: `327 tests passed`
- Pass 5 authority suite: `131 tests passed`
- Pass 6 action/orchestration suite: `144 tests passed`
- Complete pytest suite after current-baseline implementation: `1202 tests passed`
- Stage 4 Pass 1 focused suite: `65 tests passed`
- Stage 4 Pass 2 focused suite: `52 tests passed`
- Stage 4 Pass 3 focused and golden suite: `115 tests passed`
- Stage 4 Pass 4 runtime/CLI/closure suite: `13 tests passed`
- Stage 5 Pass 1 Doctor query/case/engine suite: `23 tests passed`
- Stage 5 Pass 2 enumeration query/population/aggregation/engine suite: `52 tests passed`
- Stage 5 Pass 3 source/query/projection/comparison/golden suite: `121 tests passed`
- Stage 5 Pass 4 workflow/guided/runtime/closure suite: `21 tests passed`
- Complete unittest discovery subset: `458 tests passed`
- Read-only audit: `PASS`

Stage 2 is complete. Stage 3 Passes 1-6 and Pass 6 live structure verification
are complete. Formal closure is `STAGE3_COMPLETE` with zero concrete blockers;
accepted limitations are recorded in `stage3_closure_assessment.json`. Stage 4
is **COMPLETE** with Passes 1-4 complete and zero concrete closure blockers.
Stage 5 Passes 1-3 are complete and Pass 4 remains the active closure scope.
The additive current-baseline path validates the existing private scenario
manifest, requires the exact `GET_ONLY_CURRENT_BASELINE` confirmation, accepts
the hidden token only through child standard input, and exposes only login,
guild, role, channel, and two exact-member GETs. It immediately minimizes and
pseudonymizes the memory-only responses, emits no source-ID map, and calculates
through the frozen Stage 3, Stage 4, and Stage 5 public interfaces. Replay runs
in a separate token-free, network-free process. Offline readiness and 1202
pytest tests pass, but the live acquisition has not run; therefore source
results, exact replay, and formal closure are still pending. No Discord request
or write occurred during readiness, and Stage 6 has not started.

## Stage 5 Pass 4 local workflow usage

`guild-doctor-doctor guided --snapshot <snapshot.json> --query <structured-query.json>`
starts the deterministic terminal selector. It requires exact numbered options,
registry keys, or decimal object IDs for the question, subject, context, target,
and presentation choices, then emits a review record and requires `CONFIRM` or
`CANCEL`. The structured query file carries required evidence that cannot be
inferred from a partial snapshot; arbitrary natural-language questions, fuzzy
matching, credentials, network options, and Discord command registration are
not accepted.

The local CLI also provides `why`, `who`, `find-setting`, `compare-roles`,
`run`, `batch`, `validate`, `verify`, and `close-stage5`. The future Discord
mapping is documented only: WHY to `/guild-doctor why-can` and
`/guild-doctor why-cannot`, enumeration to `/guild-doctor who-can`, source
location to `/guild-doctor find-setting`, and role comparison to
`/guild-doctor compare-roles`. None of these Discord commands is implemented
or registered in this checkpoint.

## Stage 5 current-baseline live runner

After reviewing `stage5-current-baseline-evidence/acquisition_readiness_report.json`,
Jesse may start the authorized capture in Windows PowerShell 5.1 with:

```powershell
powershell.exe -NoProfile -ExecutionPolicy Bypass -File "C:\GuildDoctor\RUN_GUILD_DOCTOR_STAGE5_CURRENT_BASELINE.ps1"
```

The runner performs offline readiness first, requires the exact disposable-guild
confirmation, prompts securely for the token, passes it only over child standard
input, and starts replay only after the acquisition child has exited and the
token has been cleared.

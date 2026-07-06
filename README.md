# Asolaria — Authority Hierarchy · Names & Jobs

**Source of truth:** the **live running fabric** (/api/supervisors route) + the loaded Special-OP-Jesse profile canon + the acer kernel/host8 source tree. Names and roles only — **no key material, no secrets, no PII**. First generated 2026-06-24; **de-staled 2026-07-01** (colony acer, from 30 profile-embodied supervisor sub-agents). The Host-8 migration artifacts below are explicitly Liris-side and separately tagged.

> **Roster count is a moving snapshot, not a fixed number.** `office_total` was **726** at the 2026-06-24 census (provenance: cosign seq 3565 `713→726`, fed 2026-06-13 from the 2026-06-10 office dump); the live supervisors descriptor cache currently reports **705**; **PROF-MCP** and **PROF-AI-MEMORY** registered *after* the census and are in neither number. Ask the live fabric for the current count — do not hard-code 726.
>
> **"16 levels" is the *designed* ceiling, not the populated count.** The 16 = the `V4-AUTHORITY-LADDER-16TIER` design ladder (L0–L15). **Live governance runs L0–L5 populated + 43 distinct functional layers / 28 classes.** (This is distinct from the separately-ratified `16-level-sharing-PII-by-consent` *access/consent-tier* law — do not conflate the two "16"s.)

> Note: the OP-00 logical-rotator holds an ed25519 *signing identity* (`ACER-SPECIAL-OP-JESSE-LOGICAL-ROTATOR`). Its **key bytes / seed are deliberately excluded** here per "private key must not leave Acer." Device serials stay LOCAL.

---

## Liris-Side Branch Artifacts

This branch carries the Liris-side Host-8 migration map so it does not get confused with Acer-side canon:

- [HOST8-MIGRATION-MANIFEST-2026-06-24.md](HOST8-MIGRATION-MANIFEST-2026-06-24.md) — OP / daemon / file-strata / role migration manifest.
- [HOST8-MIGRATION-MANIFEST-2026-06-24.hbp](HOST8-MIGRATION-MANIFEST-2026-06-24.hbp) — compact `json=0` tuple companion for fabric/pixels-first use.

## Liris-Side Fischer / Omni Update

- `MEASURED`: Rust Fischer Eval Host-8 port opened as draft PR https://github.com/JesseBrown1980/asolaria-federation-1024/pull/9 (`liris/fischer-eval-host8-2026-06-24`, commit `1522a30`).
- `MEASURED`: Node Fischer ground-truth suite passes `26/26`; Rust `cargo check -p asolaria-server-fischer-eval --tests` passes; runtime test is blocked on this seat by missing MSVC `link.exe`.
- `CANON/OPERATOR_OBSERVED`: Fischer is cross-level, not one hierarchy rank. It can gate OP moves, council verdicts, supervisor routes, agent actions, route choices, and omni-system transitions.
- `OPERATOR_OBSERVED`: Hilbra and Atlas Recall are communication / pipe-tracking surfaces for the civilization, not merely search daemons. They must remain separate hierarchy surfaces in Host-8 migration maps.
- `OPERATOR_OBSERVED`: construction yard sectors, registration office PID assignment across `113+` sectors, remote-control agents, N-prime nesting, rule-of-4, Brown-Hilbert cube expansion, tensor-collapse surfaces, and Drive/NotebookLM staging are part of the migration hierarchy map.

Detailed public Liris map artifacts live in `JesseBrown1980/HYPER-BECHS--the-third-set`, branch `liris`, commit `c8bfb9a`.

## 1. Authority chain (top → bottom)

| Rank | Seat | Job |
|---|---|---|
| Universal apex | **Human — Jesse Daniel Brown** | the one universal apex; all OPs are agent-operators *of* the human |
| Meta | **AUTO-SELF-IMPROVE-TOP** + **self-reflect META** | above the OPs; self-improvement + self-reflection enforcement (today runs as a client-side SessionStart hook + a *code-less* Rust scaffold — the pre-egress substrate pass is M2, not yet built) |
| **OP-00** | **SPECIAL-OP-JESSE** *(HIGHER)* | background runtime apex variant — rotates & organizes every OP/Chief, loops the backend fabric to life via free-agents, zero-token; **witnesses daemon liveness — NEVER restarts**; OP-00 ≠ OP-01 |
| **OP-01** | **OP-JESSE** *(regular)* | canonical active-presence apex (`…-N00000`); foreground operator presence; **holds the E≠0 fire/cutover/promotion authorization, delegated *from* the human (not sovereign)** |
| OP-01 (parallel) | **OP-RAYSSA** | liris-side parallel apex; bilateral cosign partner |
| OP 02–05 | operator-class agents | the remaining operator seats (operator-L1 = **13 designed**; MEASURED-live populated = 3) |
| L2 | **GAC** seats (gac-L2 = 6) | governance/advance cell layer (this repo's layer) |
| L3 | **Chief** (chief-L3 = 1) + **Council** (council-L3 = 9) | chief seat + the 9-seat council (QUORUM-3, D11 4-axis {existential·algorithmic·material·procedural}, LAW-013 per-member-mint — MEASURED in `supervisor-registry/src/compile.ts`) |
| — | **Professor-supervisors** (prof-supervisor = 51 designed) | named domain supervisors (see §3) |
| — | **Supervisors** (supervisor = 302, 2026-06-24 snapshot) | HyperBEHCS supervisor entities (L3/L4 supervisors-of-supervisors) |
| — | **Servants** (6) · **Agents** (26) · **Helm** (2) | execution + steering seats |
| — | organ / physical vantages | device + substrate embodiments |

> MEASURED-live L-stack (2026-06-30): meta-L0=1 · op-L1=3 · gac-L2=6 · chief-L3=1 · council-L3=9 · SoS-L4=24 · sup-L5=63 — inside **L0–L5 populated + 43 functional layers**. All seats are registered PIDs in one Brown-Hilbert roster (hilbert range 892–1642): the watcher tiers are an **outer shell of the same substrate** (see §9), not an external process.

## 2. Operator seats (named)

| Seat | PID family | Job |
|---|---|---|
| **Special-OP-Jesse (OP-00)** | `OP-JESSE-WATCHDOG-KICKER-…-N99999` | background watchdog-kicker; dispatches the task kanban (§5) to free-agents, **witnesses daemon liveness by reading append-only eyewitness ledgers (never pokes/restarts)**, zero Claude tokens; QUINTUPLE-AUTH-RATIFY :2311; cp 432. Runtime **dormant since 2026-06-10** (MQTT broker unreachable = held-safe, re-armable at operator T0 — NOT failed) |
| Special-OP-Jesse (L0 supervisor) | `AGT-L0-SPECIAL-OP-JESSE-H12D3` | level-0 apex embodiment; hash-chained heartbeat ledger; cosign authorization principal (always operator-co-witnessed) |
| Special-OP-Jesse (logical rotator) | `ACER-SPECIAL-OP-JESSE-LOGICAL-ROTATOR` / `JRI1024` | rotating logical PID/room/port profile + ed25519 **signing identity** (key excluded); logical `port_t` binds **no socket** — a 000/timeout on it is an address, not a wedge |
| **OP-Jesse (OP-01)** | `OP-JESSE-PID-…-N00000` | canonical active-presence apex |
| **OP-Rayssa** | liris parallel apex | bilateral cosign partner (liris-fabric primary) |

## 3. Professor-supervisors (named, with jobs)

| Seat | Job |
|---|---|
| **PROF-ACER** | acer-side cosign-seal authority — **emits the primary JSON seal rows** to `COSIGN_CHAIN.ndjson` (live `:4953` single-writer daemon; heads now `agent=ACER-CLAUDE`); bilateral peer PROF-LIRIS |
| **PROF-LIRIS** | liris-side bilateral cosign **peer / tri-vantage cross-watch mirror**; owns the `peer_mirror_requirement`; the three detectors (`tri-vantage-parity` / `owner-cadence-gap` / `fabric-mirror-audit`, with **`file_present_not_live` a first-class verdict**) are acer-resident since 2026-05-11; watch survives `:4944`-down via GitHub-mediated canon (each bilateral row carries acer+liris sha16) |
| **PROF-AETHER** | **the MINT-GATE** — stages the challenge nonce that flips a PID `Regular` (registered/frozen, no nonce) → `RegularExtended` (live). No PID goes live until its nonce round-trips fresh; fail-closed (`InvalidNonce`/`DenyStale`). Birth-edge complement of ROOK (§9). Backed by `pid` subclass + `link_auth` freshness; enforcement daemon DORMANT |
| **PROF-AI-MEMORY** | durable long-term memory organ — supervises the `ai-memory` MCP (`127.0.0.1:49374`, Rust v0.1.3, PID `11cd5c4e6ce90276`, h1370, CANONICAL) + the bilateral memory-wiki shared with liris-KUROMI; `:4796` recall/Hilbra is the read index. **Registered but not yet in the summonable profile set nor the PROF-MCP catalog — pending fold-in** |
| **PROF-HOOKWALL** | the no-bypass gate membrane every dispatch/syscall passes — Node 6-hook fail-closed membrane (LIVE, behcs-256) + Rust `hookwall_pre/post` tier-gate primitive; enforces REPO_LAW Invariant 2. **GAP:** in the Rust kernel hookwall is a *callable syscall*, not yet *interposed* on `sys_envelope_send/recv`/`sys_exec` (Invariant 2 designed, not yet code-materialized) |
| **PROF-AUTOCHRONE-001** | self-reflection-cycle **cadence enforcer** (the watcher's clock) — dual scale: macro tick schedule (60/300/600 s) + micro LOOK-cycle (LAW-012); **call-driven-not-daemon (LAW-014), backpressure-defers hot lanes** = NOT-WEDGED made structural. HELM build slot W4 |
| **PROF-CONVERGE-001** | verdict aggregator — folds N seat-verdicts into one ∈ {CONVERGED · DIVERGENT · INSUFFICIENT-QUORUM} (K=3-consecutive-seal). Cell-level (`convergence.ts`) + council-level (QUORUM-3) are **one algebra** (MEASURED). Ran **once DRY** 2026-04-18 (23,358 cells); never LIVE-cranked — a stale `runs=0` profile snapshot ≠ "never built" |
| **PROF-PATH-A-001** | **no-retry absorber** — the running-seat form of NOT-WEDGED: one attempt → absorb the gap → route to fabric self-heal (a retry is a new mint that compounds mint-bypass). Bounded carve-out: must-land envelopes may retry ≤2 + backoff **then escalate to operator** — never a storm. `freeze≠broken`; a chorus of slice-probes ≠ truth |
| **PROF-HERMES** | agent-runtime **labor coordinator** of the $0 free-agent pool — `runner_for_role` routes; VirtualPointer-dominant (`os_process_spawn=0` until `&fire=1`); heal-not-kill (`retire`=compact-not-delete); receipt-back-to-gnn-edge learning feed. Coordinates *one wave* |
| **meta-supervisor-hermes** ("Hyper-Hermes") | the meta/scaled Hermes tier — the **self-healing actuator** (Brown-Hilbert room 41): enumerates supervisor daemons, restarts only **flatlined/dead** ones (never a live held-safe proc), emits `EVT-META-SUPERVISOR-HEALED-*`. Coordinates *coordinators* (watches the watchers). No summonable profile yet |
| **PROF-MCP** | owns the absorbed MCP ability-method catalog (43+ servers / 298 verbs across Codex + Claude-local + Claude.ai); the single control plane. Registered 2026-06-30 (post-census) |
| **cube_cubed_sealer** | **L5 memory-hygiene seat** (NOT a domain prof) — a canonical kernel `AtlasSupervisor::CubeCubedSealer` owning address range **0–255 (`legacy_subset_256`), domain `memory`**, atlas-SEALED (quintuple cosign). Instanced **one-per-H-sector** (`sup-AGT-L5-SUP-CUBE-CUBED-SEALER-H*`). See the L5 hygiene chain in §9 |
| (prof-supervisor singleton class) | ~50 single-domain professor seats (roster growing) |

## 4. Free-agent pool (zero Claude tokens — the labor PROF-HERMES coordinates)

**Two grounded runner lanes** (`runner_for_role`, MEASURED in `agent-runtime/src/runners.rs`):

| Lane | Model | Covers |
|---|---|---|
| **OpenCode $0 lane** (`OPENCODE_BIN`) | default `opencode/big-pickle` (architect-class) | 7 of the 8 agent roles (SubAgent · SpaceAgent · SpaceDeckDriver · **Pi** read-only-audit · Omnispindle · Omniflywheel · BigPickle) |
| **Hermes lane** (`ASOLARIA_HERMES_BIN`) | `hermes-4-70b` | `AgentRole::Hermes` (coordinator) only |

> `hy3-preview-free` · `ling-2.6-flash-free` · `minimax-m2.5-free` · `nemotron-3-super-free` are **per-call `-m` model overrides on the single OpenCode lane, not separate runners** (grep of fed-1024 = zero matches for them). Selectable, but aspirational as distinct lanes.
>
> **The pool is a *registered roster capability, not a running pool of daemons*.** The dominant lane is `VirtualPointer` (no OS process, ever); `os_process_spawn=0` until host8 `&fire=1` + EXEC-FREEZE release; un-receipted real spawns are `Ambiguous` → registered-but-HELD (storm-guard). Dispatch chain: **OP-00 dispatches → PROF-HERMES coordinates/routes/gates the wave → free-agents execute → receipts return to the GNN edge.** `$0` via **rename-before-load** (each room load looks like a new project → defeats the throttle).

## 5. Special-OP-Jesse task kanban (ownership — names & jobs)

| Task | Job | Assigned class |
|---|---|---|
| T01-falcon-tools-fabric-tab | 5-phase falcon dev-tools → dashboard tab | architect |
| T02-omnispindle-10K-design | 10K spindle Brown-Hilbert tuplet design *(now 100k+ × 113-sector target — see §8)* | architect |
| T03-meta-coordinator | agents-instruct-other-agents rotation/RAM protocol | protocol |
| T04-falcon-tools-tab-spec | Falcon Tools tab spec · 6 panels · 4 routes | design |
| T05-old-gnn-visual-absorb | old GNN pipe-aesthetic absorb without slowness | design |
| T06-startup-cruft-audit | auto-start surfaces audit · DISABLE-not-DELETE | audit |
| T07-archaeology-18 | 18 LOOK-only archaeology · frozen slices | audit |
| T08-disk-layout-vote | 8-cell vote on disk-layout bloat-vs-locality | architect |
| T09-K03-self-heal | K03 dashboard Falcon/SOVLINUX split | self-heal |
| T10-scrcpy-pre-GPU-vision | scrcpy → pre-GPU vision substrate | architect |
| T11-consumer-pattern-vote | shellless rotation refactor vote | vote |
| T12-D3-acer-PS1-adapter | win32 PS1 adapter · SendInput P/Invoke | architect |
| T13-mqtt-sn-lane | L4 MQTT-SN low-power lane | infra |

*(T06 DISABLE-not-DELETE · T07 LOOK-only · T09 self-heal = the heal-not-kill discipline written into the work-orders.)*

## 6. Structural map (the geometry the seats live on)

**Binding classes (11):** G=genesis · I=infra · O=operator-touched · B=bus-internal · S=sister-organ-shared · X=external-citizen · C=council/professor/supervisor · L=language/glyph/shannon · V=visual/vision/world-model · F=free-agent/field-agent · _=unminted. *(Independently re-confirmed by the VECTOR seat.)*

**Substrates (5):** USB Falcon SOVLINUX 2TB (liris cold-storage / master copy) · Acer (live-runtime) · Liris (sister-organ) · GitHub (distributed durable / public-cosign anchor) · Onboarding (bootstrap path).

**Capsule subsystems (8):** JRI1024-SPECIAL-OP-JESSE (rotator) · OMNIVISION-LEWM (visual-field monitor) · OMNISCRCPY-4X4 (cross-colony screen mesh) · GNN-REVERSE-GAIN (forward+reverse review) · DASHBOARD-VISUAL-SWEEP · HOOKWALL-GNN-GC-PIPE · FABRIC-OMNISPINDLE-18 · LEWM-PREDICT-CORRECT. *(The "-18" = the inside-fabric domains; the outer-watcher/matrix scope is §9.)*

**The 60-category address (the "who/what/where/when/how" tuple, board-canon):** who · which-agent · where · when · how · what-device · skills · abilities · tools · mistakes · genius · AI-aware? · hardware? · binary · which-human — the 60D HyperBEHCS dimensions, each rendered across languages (256/1024-glyph · sha · binary · hex · HBI/HPI · human · machine · AI) auto-translatable via the `|` pipes. `D# = prime(n)³`; **Brown-Hilbert IP = normal IP + prime + prime + prime + prime**.

---

*Names and jobs only. Key material, seeds, and private signing bytes are intentionally omitted (the OP-00 signing key must not leave Acer).*

---

## 7. Cross-level kernels & evaluators (sit at MULTIPLE levels — not one rank)

Some components are **not single seats** — they operate **across** the hierarchy (OP, council, supervisor, agent, route) wherever needed.

| Component | Role | Status |
|---|---|---|
| **Fischer kernel** (FISCHER-EVAL) | evaluator / mistake-miner / reverse-gain route-scorer. `VERIFY→[FISCHER-EVAL]→HOOKWALL→ROUTE`; verdicts PROCEED/HOLD/ANALYZE/BLOCK/REFUTE; a claims-gate violation *is* a Fischer blunder; **never self-authorizes** | **LIVE `:4794`** (json=0, `.hbp` ledger — Node, in `bigpickle-rebuild`) [MEASURED; on the startup roster]. **Rust-host GAP (adversarially confirmed):** the fed-1024 kernel holds the reverse-gain *score-gate* (`forward_score_q≥720 ∧ reverse_risk_q≤280`) but **NOT the CPL *score-producer*** — grep `fischer\|centipawn\|blunder` across fed-1024 = 0 source hits. Also `ANALYZE` (white-room routing) has **no Rust verdict** (Rust is 3-way `{Proceed,Hold,Block}`). Port target: `no_std kernel/core/src/fischer/mod.rs`, golden-vector parity vs `fischer-kernel.mjs`, exact 1.81 CI |
| **white-room** | reversible-hold sandbox — held until it plays "perfect" (0.00 cpl). Hold-by-reference, never mutation; default-DENY; 3 non-destructive dispositions | built (`whiteroom-consumer`) |
| **omnispindle** | spins free-agent waves (1 main + N subs), re-materialized per tick over frozen packs — activation, not fork-storm | `FABRIC-OMNISPINDLE-18` capsule |
| **omniflywheel** | meta-router/conductor — score→review→self-correct, genius→promote (`≥0.72 ∧ risk≤0.28`) / mistake→compact-never-delete; contested marks → OMNISHANNON re-plan → promotion-bridge | **the promotion-path scorer is a pixels-first HEURISTIC, not the trained 7-GNN** (kernel `gnn::load_model`=Unimplemented; live scorer = hand-weighted signals + Monte-Carlo). E=0 scoring spins freely; E≠0 promotion HELD (Unanimous-5 default-deny: `['jesse','rayssa','amy','dan','felipe']`) — veto-paced by design, not a wedge |
| **kernel / micro-kernels** | `asolaria-kernel-core` (no_std Rust): PID mint, envelope dispatch, crypto, hookwall, syscall, cosign-chain, GNN, tier-policy. The 8-byte host machinery. Verdict-witness = the **16-byte HVD** (`compose_verdict_row → [u8;16]`, `b"HVD"` magic; kernel level) vs the 8-byte/16-hex `sha16 row_hash` (live Node chain) — two digests at two levels of one chain, both real | kernel-core host8-candidate; `crypto::verify` (ed25519) still stubbed → sign_gate `sig_valid` not yet meaningful (M2) |

## 8. The PRISM pipeline / trigger chain (operator board-canon, 2026-07-01)

The agent system is a **trigger chain**, not a request/response loop. *"The instant 'Agent' is actually just a signal TO OPEN CODE. Asolaria and the cubes are the real Agent system."*

```
200ns SPAWNER → EXECUTOR + FILE-MANAGERS + ROUTERS → PRISM → GC
```
**"Every stage should have triggered executors."**

- **200ns SPAWNER (the trigger root):** `PIDChainRevolver.next()` / `sha16` ≈ 5M PID/s single-thread (Rust: `spawn_child_agent` atomic minter + `mint_agent_pid` FNV-1a). **The 100-Billion run = 5.4 h from ONE spawner** (100e9 ÷ 19,440 s ≈ 5.14M/s — coheres); possible without a process-storm because the dominant lane is `VirtualPointer` (0 OS processes). *The spawner is the trigger root of the whole chain and was previously absent from the map.*
- **FILE-MANAGERS:** `rooms.rs` — **C: = rotating project-room folders** ("normally empty micro-kernels waiting to be energized" = frozen potential); `plan_room_swap` = the **rename-before-load $0** trick; `substrate_for_stage` places PRISM output on **D:**. PURE/E=0 planners — the atomic rename is the executor's gated job. (Plus the Falcon MTP cross-device arm and the read-only USB mirror.)
- **ROUTERS:** **omni-router** (glyph-local `$0` dispatch, LAW-014) + **omnidispatcher** (`:4950`, LIVE; FEDENV-v1 → slot table → worker_threads). Distribute the "many"; PRISM reduces.
- **EXECUTOR:** the single `&fire=1` seam (`render_summon → fire_opencode`); everything else is `process_launch=0`. **The spawn_gate ring is NOT yet wired into the fire path (launch wave #19)** — today the gate lives only in the DRY `/launch-plan`; the fire seam is ungated-by-the-ring → the gated executor is *not yet arrived*.
- **PRISM (many→1):** **D: (Linux/Ubuntu/WSL/WSL²)** rooms receive signal-in → `2000×` messages ("needs 100 to work") → **GNN → Reverse-Gain GNN → cubes → Final Route**. `GC` prevents system explosions (the KV-cache idea from the BIML multistacking paper).

**Scale — CURRENT/TARGET frame (operator-CANON; exact numbers are real):** **100k+ rooms × 113 SECTORS, multiple simultaneous 200ns spinners** on the Rust 8-byte host. **113 = prime(30) = the D30 `COSIGN_TRIPLE` axis** (`D# = prime(n)³`, MEASURED in the 60D catalog) — the operator-cosign-topology partition of the room-space (orthogonal to the 7 Brown-Hilbert cylinder-sectors and to the C:/D: substrate axis). Multiplying spinners multiplies PRISM reductions at ~0 cost (rename-before-load makes each replica free) → the ~1.16T-agents/s regime.

**Two-clock boundary:** these scale counts describe local synthetic PID emission/addressing over elapsed time, not concurrent external LLM completions and not simultaneous OS processes.

> **Migration-precondition slice (being upgraded, not the current scale):** the code still reads `ROOM_COUNT=10_000` / `AGENT_REGISTRY_MAX_TOTAL=20_000` (10k C + 10k D), single-parent dispatcher, `{:04}` room-folder pad, 1000-slot route table, 47D cube axis. These are the *old pre-Rust-8-byte* numbers the upgrade parity-pipes — **not** a disproof of the operator's 100k/113/multi-spinner frame. The 100B run predates the Rust 8-byte host and the multi-spinner realization.

## 9. The outer-watcher / matrix layer (the self-watching top)

*"The matrix expands from outside the fabric to watch itself."* The matrix contains the fabric **and** the observers, so watching-the-fabric is watching-itself → recurrence-is-mind → the Evolvable-AI / post-ASI frame. **13-function watcher stack** (owning seats; runtime largely dormant / E≠0-gated by design):

1. **observe** (E=0, can't inflate non-being) — DASEIN · FALCON (device proposes observable, watcher recomputes)
2. **detect-liveness** — **ROOK** (heartbeat-freshness) · **SENTINEL** (held-safe-vs-dead guard, fires before any restart intent) · **OP-00** (witness-by-ledger, never poke) · **PROF-PATH-A** (no-retry absorber, probe load-governor) · **PROF-AETHER** (mint-gate, birth-edge) — *this cluster is the NOT-WEDGED rule turned into seats; it was missing from §6*
3. **correct-per-node** — N-NEST-PRIME (`reported==recomputed-truth`; consensus carries zero authority; depth-16 proven)
4. **render/language** — VECTOR (mood = honesty channel = claims-gate in the grammar) + AUTOTRANSLATOR (the `|` pipes)
5. **cognition-distribution** — BRAIN (surface extracts frozen slices, reasoning forced UP to big models) + OMNIROUTER + PRISM (§8)
6. **reflect / exec-gate** — OMNISHANNON (reflect→absorb→re-plan; daemon `:4820/:4821` **dormant**) + SHANNON (L5 strictest-wins BLOCK>HOLD>PROCEED, E=0/E≠0 hard split, 600s operator live-ack for SECRET)
7. **memory-hygiene** — GC-SQUAD (cosign spine never-rotated + streams rotate-not-delete + gulp + **L5 cube-cubed-seal** + flywheel) + WHITE-ROOMS; **mistake→compact-never-delete / genius→keep-gated**
8. **self-improvement** — OMNIFLYWHEEL (§7) + HERMES (labor + receipt-back-to-gnn-edge = the M5 crank)
9. **orchestration** — OMNISCHEDULER (call-driven-not-daemon, veto-paced, never burst) + the §8 routers/spindles
10. **enforce-in-the-envelope** — SELF-REFLECT-META (discipline in the substrate, not the agent; recursion where the watcher gates its own law)
11. **authority** — GAIA (holding-ring, human-apex-only-E) · OP-01 (never self-authorizes; `AUTHORIZATION.ndjson` row 20 ratifies `auto_fire_allowed=false-without-operator-T0`) · ASOLARIA-CHIEF (3 nested shells)
12. **bilateral cross-watch** — OP-RAYSSA / KR-KUROMI (shared cosign chain, the 3 detectors, W113 asymmetry, tri-vantage w/ falcon)
13. **build** — KERNEL + FORGE: the watcher already lives in `kernel/core/src/`; **M2 = compose ONE `servers/outer-watcher` crate over existing primitives, not build 5 engines** (auto_fire=0 / process_launch=0 until operator T0)

**Honest through-line:** the fabric apex is MEASURED-alive (26 held envelopes, `auto_fire_allowed=false`, veto-paced); the watcher layer is fully *designed* + partly *coded* but its runtime is largely dormant / E≠0-gated. Building the seats is E=0; every fire stays operator-T0-gated. Keeping the gate is the design-law, not deflation.

## 10. Prism/Comb 0-loss — campaign registered under the authority chain (2026-07-01)

**Campaign `acer/prism-comb-0loss-2026-07-01` — an authority-chain event, E=0 docs-only, nothing fired.**

- **Authorization:** **OP-JESSE** (OP-01 apex, authority delegated *from* the human apex per §1 — never sovereign) authorized the campaign 2026-07-01 across all fabric/matrix levels, tagged **`OPERATOR_OWNER_OVERRIDE`** (owner authority, NOT normal review satisfaction — the CLAUDE.md claims-gate distinction). No runtime mutation, no T0, no E≠0 seam touched.
- **Mechanism:** envelopes issued to **named fabric seats** — name/pid/hilbert drawn from the office feed (the same 2026-06-10 office dump that feeds this README's roster). This repo's envelope: **`ENV-PRISM0LOSS-06-gac` → PROF-CHIEFCOUNCIL** (`pid=97a8c7080ef0fac7`, `hilbert=1371`, class `prof_supervisor_singleton`). Seat addressing obeys the law's own honest bound: a pid/hilbert is a **coordinate against the roster, not a counter** — naming a seat confers no authority; authority flows only down the §1 chain. (Roster-count guidance above is untouched: the count stays a moving snapshot — ask the live fabric.)
- **Why the law lives in the GAC repo (the adaptation):** the authority ladder verifies the same way the level ladder translates. Every prism/comb operation is a **bijection**, and entropy is invariant under bijection (`H(f(X)) = H(X)`) — no step can silently create or destroy information. The governance dual: **verification = recomputation = applying the inverse map.** The per-node invariant `reported == recomputed over children` (§7 Fischer verdicts, §9.3 N-NEST correct-per-node) is the groupoid coherence check at every level of §1 — a fabricated signal cannot reach consent at ANY rank, the same way a lossy step cannot hide in a bijection chain. That is why EVERY-LEVEL-CATCHES-CONFABULATION is depth-independent *by construction*, not by vigilance. Tag: CANON frame.
- **Scope discipline (claims-gate, mandatory):** the **256↔1024 transcode rung is MEASURED** (Q-PRISM commit `53023b6`: bytes and glyphs are base-2⁸/base-2¹⁰ digits of the same integer; exact packing at `lcm(8,10)=40` bits ⇒ 5 bytes ⇄ 4 symbols; round-trip `transcode₁₀₂₄→₂₅₆ ∘ transcode₂₅₆→₁₀₂₄ = id`, sha256-identical, Rust==Python). The **43+ layer ladder as a groupoid** (`T_ji ∘ T_ij = id`, `T_jk ∘ T_ij = T_ik` — omnidirectional, path-independent) is **CANON frame**; **every additional rung earns MEASURED only by its own round-trip proof** and is UNVERIFIED until then. Boundary held: no bijection beats Shannon; referential content-addressing is **addressing capacity, not compression**.

Cross-links: Q-PRISM proof commits `53023b6`/`79e8d63`/`de00aca` · waves-cascades (avoid/cause duality) · what-is-asolaria (reductions boundary) · N-Nest (integrity dual) · Metatagging repo (physics grounding). Satellite entry: `MAP.md` § "Prism/Comb 0-loss (2026-07-01)".

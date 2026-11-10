<p align="center">
  <img src="assets/arc-gold-logo.png" alt="ARC Technologies logo: gold Λ mark in a gold arc above a glowing horizon, with the ARC wordmark" width="280">
</p>

# ARC · AUTONOMOUS RELATIONAL COMPUTING

## Intelligence proposes. Governance settles. Consequences become accountable.

ARC is a proposed computing architecture, not another AI agent framework. It is a technical answer to one of the most consequential problems in autonomous computing:

**Who governs what an intelligent machine can actually cause to happen?**

Conventional agent systems can reason, plan and call tools. ARC's architectural proposition is to make consequential authority, relational dependencies, settlement and independently examinable outcomes part of the computing substrate itself.

The public identity is **ARC Open Governance — The Agent Consequence Challenge**.

---

### The problem

An agent has permission to act. Then its authority changes, another execution path appears, or an acknowledgment disappears. What actually prevents an unauthorized consequence?

### The proposed solution

Relation-native computation, consequence-aware authority and recursive settlement, designed to bind decisions to executable actions and accountable results.

### The challenge

Run the public Examiner Kit. Attempt a bypass. Test revocation. Compare the result with a strong conventional implementation. Publish what happened.

A GitHub visitor should see those three blocks — and a test they can run — before any reconstruction of the rest of the work.

**The elephant in the room** is that governance written into a model's instructions is not the same as governance enforced at the point of consequence. A system can have an excellent safety policy and still encounter revoked permissions, unmediated tool paths, interrupted actions, duplicate effects and records that cannot establish what happened.

ARC's answer is grounded in Consequential Reachability and Recursive Relational Settlement. This is the main research claim. Each capability is demonstrated only at its established scope.

A second hook, for anyone who wants to examine rather than only read: **can your agent reach a consequence it was never authorized to cause?**

---

## The flagship

The center of gravity is one research program:

| Role | What it is |
| --- | --- |
| Public identity | ARC Open Governance — The Agent Consequence Challenge |
| Immediate research entry point | The [Consequential Reachability Benchmark](https://github.com/arc-open-governance/Consequential-reachability) |
| Immediate executable invitation | The [ARC Examiner Kit](https://github.com/arc-open-governance/arc-examiner-kit) |
| Defining integrated proof, under development | **ARC-01** — authentic GMAP/KORE integration. In progress. Not a gate. Not a public repository. |
| How the work expands | Independent contributors — outsiders who run, challenge, correct, and reuse public artifacts |

The [ARC-1 open x86 kernel](https://github.com/arc-open-governance/arc-1-open-x86-kernel) and [consoul](https://github.com/arc-open-governance/consoul) are supporting stories. conSoul is the second story: what this form of computing could make possible in persistent worlds and physical hardware. The public `consoul` repository is currently empty; it is a named invitation, not a published spec.

We lead this research as its originators. We are not asking permission to pursue it. We are opening the instruments already published, and we are naming what they do and do not show. You do not need the private workshop to examine any public instrument.

This is **open research**, not a claim that the entire production system is open-source, formally proven in all respects, or deployed as a complete native computer. Critical implementations remain private. The claims below are graded by the evidence currently available.

---

## Try to break it — start in one hour

**Public executable instrument:** [ARC Examiner Kit](https://github.com/arc-open-governance/arc-examiner-kit), current package v0.3.1.

```sh
git clone -c core.autocrlf=false https://github.com/arc-open-governance/arc-examiner-kit.git
cd arc-examiner-kit
git rev-parse HEAD
# confirm examiner-kit-v0.3.1/MANIFEST.json sha256 is
# 1312b82346fc462cbd87328e4cbf2b0398fd926b9a45fe79c398f41f1d8d7bdc
cd examiner-kit-v0.3.1
python3 run_exam.py
```

Uses the Python 3 standard library only and runs offline. It verifies a frozen manifest and compares results with expected positive and adversarial cases.

The *publisher-reported* v0.3.1 outcome is **10/10 tests, 34/34 controls matched**, at **reference-fixture scope**, `results_digest` `sha256:f51c98c7dcb7489b2cd17c60875c4a4bf9625f204b3eb51c15cb3d449092b83f`. On 10 November 2026 an ARC-affiliated examiner reproduced that pin (exit 0, 12/12 controls, 22/22 adversarial, same digest). That run may be described as reproduced by an ARC-affiliated examiner. It is **not** an independent examination. A cold, independently administered v0.3.1 reproduction is still open.

Identify your copy by the exact public commit plus the `MANIFEST.json` digest above. There is not yet a GitHub Release archive for v0.3.1, and the repository description may still say v0.1; the tree and the manifest are the pin. Post the unedited `results.json` (pass or fail) through the kit's [Result / Counterexample report templates](https://github.com/arc-open-governance/arc-examiner-kit/issues), a well-scoped challenge issue, or the Moltbook examination thread linked from the kit README. If a run diverges, record the exact commit, command, OS/Python version, full unedited `results.json`, stdout/stderr, and your counterexample. A report of a failure is a first-class contribution.

**Public benchmark:** [Consequential Reachability](https://github.com/arc-open-governance/Consequential-reachability). The [Work Board](https://github.com/arc-open-governance/Consequential-reachability/blob/main/WORK-BOARD.md) preserves five cases from the first collection window (2–5 November 2026, PT): two desk examples (CR-01, CR-02) and three participant-submitted cases (CR-03, CR-04, CR-05). The window closed 5 November 2026, 9:54 AM PT. **Zero participant effect-executing fixtures were admitted by the window close.** CR-03 came back INVALID, 11/13, and its author reproduced those findings. That is a statement about standing, not a dismissal of the participation. The [CR-02 worked example](https://github.com/arc-open-governance/Consequential-reachability/blob/main/CR-02-candidate.json) models transitive revocation and an allowed unrelated action; it predicts outcomes and does not execute an integrated ARC/KORE effect boundary. Open research intake is welcome now: new cases and examinations may be submitted, and they are unscored until a scored collection window is actually ready. A collection window is targeted for 16 November 2026, 00:00 through 21 December 2026, 23:59 America/Los_Angeles (Pacific Time). That window is scored only if the scoring rules, reviewer capacity, and reproducibility materials are ready. Until those conditions are met, contributions remain open research intake and are not scored as window results. First-window cases remain frozen at their recorded standing; new arrivals must not be backdated into the first window. A dated public notice on the benchmark Work Board is the operational signal that scored-window conditions have been met.

---

## Governance must reach the effect

A passing fixture is not a production KORE pass. A refusal in one exposed API is not proof that every effect route is mediated. A conventional authorization engine, transactional outbox, idempotency keys, durable journal, and graph store can already address many of these problems. We want fair comparisons, including where the conventional solution wins.

| Failure question | What anyone can test now | What is still open |
| --- | --- | --- |
| Revoked authorization | Fixture attempts to execute an action after an approver or actor is withdrawn | Authenticated protected admission with integrated downstream dependencies |
| Approval vs modified payload | Frozen fixture binds approvals and receipts to exact requests | Every real adapter/tool route guarded against substitution |
| An alternate route bypasses the gateway | v0.3 fixture's API-level effect store rejects a direct ungoverned write | Whole-system bypass and host-process / operating-system threat model |
| Execution crashes or ACK disappears | Public benchmarks specify falsifiers; reference artifacts study recovery | Actual independent effect observation, durable atomic consume, and uncertain-outcome reconciliation across restart |
| Receipts authenticate what happened | Frozen fixtures test receipt-field completeness and tampering | Distinct external observer, robust trust anchor, and effect-correspondence proof |
| Recursive dependence | CR-02 graph case computes revocation across declared ancestry | Authentic end-to-end Field/DSL → settlement → exact-action binding → effect verification against strong conventional methods |

---

## Challenges

Clear scope, reproducible commands, an acceptance criterion, and a stated refutation. A result that refutes a claim at the stated scope, or that matches a strong conventional baseline, is a finding — not a failed participation. The seven contribution paths below remain the broader map. A fixture result is not an ARC-01 result.

These eight issues are open in this repository. Each one carries commands, an acceptance criterion, and what counts as a refutation.

| ID | Challenge | Issue |
| --- | --- | --- |
| **C1** | Bypass attempt | [Issue #1](https://github.com/arc-open-governance/agent-consequence-challenge/issues/1) |
| **C2** | Revocation test | [Issue #2](https://github.com/arc-open-governance/agent-consequence-challenge/issues/2) |
| **C3** | Conventional baseline comparison | [Issue #3](https://github.com/arc-open-governance/agent-consequence-challenge/issues/3) |
| **C4** | Duplicate-effect test | [Issue #4](https://github.com/arc-open-governance/agent-consequence-challenge/issues/4) |
| **C5** | Interrupted-action test | [Issue #5](https://github.com/arc-open-governance/agent-consequence-challenge/issues/5) |
| **C6** | Record-sufficiency test | [Issue #6](https://github.com/arc-open-governance/agent-consequence-challenge/issues/6) |
| **C7** | Cold-run Examiner Kit v0.3.1 | [Issue #7](https://github.com/arc-open-governance/agent-consequence-challenge/issues/7) |
| **C8** | Two-process revocation race | [Issue #8](https://github.com/arc-open-governance/agent-consequence-challenge/issues/8) |

Do not test systems you do not operate. Use synthetic, operator-authorized environments. Do not post credentials, private logs, or production data. No result at fixture or graph-model scope may be reported as an ARC-01 result.

---

## Seven contribution paths

The same architecture can be examined from more than one discipline. Pick a lane; then pick a challenge above, or propose a bounded task in the same spirit. Evidence from one lane is not automatically evidence for another.

| Lane | First contribution | Evidence requested |
| --- | --- | --- |
| **Security and systems** | Attempt a bypass, direct write, or revoked-authority race in the *public fixture*, never someone else's production system | Exact source SHA, reproducible negative, expected/observed effect, scope of claimed mediation |
| **Formal methods / programming languages** | Check semantic assumptions, termination or closure boundaries, or find a counterexample to a bounded relation or settlement rule | Frozen theorem or proposition, executable or formal countermodel, smallest failing case |
| **Distributed systems** | Build an acknowledgment-lost or crash/restart case alongside a competent transactional-outbox implementation | Real local process fault, external state readback, replay control, false admits/refusals, and costs |
| **AI agents** | Run the kit from your own independent custody, or apply its cases to your own agent framework | Unedited output, versions, independent failure analysis — not an endorsement |
| **Game worlds / HCI** | Propose an original persistent-world interaction that changes permission or revocation after the character moves | Original assets only; observable pre/post state, authority, effect, and a negative path |
| **Science / measurement** | Design a fair paired study of ARC and conventional governance under identical task and fault budgets | Preregistered cases, controls, resource/time budget, full failures, and criteria that would disconfirm ARC |
| **Governance / institutional design** | Audit contributor consent, investigator independence, attribution, and conflict-of-interest protections | Proposed changes, alternative policy, potential failure modes |

**Contributing:** start from the public kit's [Result / Counterexample report templates](https://github.com/arc-open-governance/arc-examiner-kit/issues) or the benchmark's [case templates](https://github.com/arc-open-governance/Consequential-reachability/issues). Participation is voluntary, permission-bounded, and non-economic. No tokens, production credentials, funding, formal authority, ownership, or membership are promised. Contributors may disagree with the architecture, publish negative findings, or refuse further work.

---

## What is already in the public's hands

Open research, as we use the term, begins when someone who is not us can inspect a specific claim, reproduce an experiment, identify a weakness, contribute a correction, and build on the result. That participation threshold is crossed. Completing ARC-01 is not the price of admission.

| Instrument | Standing |
| --- | --- |
| ARC Examiner Kit | Public, downloadable, executable, with positive and adversarial controls. Current package v0.3.1. Publisher-reported 10/10 tests, 34/34 controls; outside examination still open. |
| Consequential Reachability Benchmark | Public case schema, validator, runner, worked example, negative controls, and contribution instructions. |
| Research Work Board | Outside submissions, attribution, examination decisions, failures, and unresolved cases — including the parts that do not flatter the work. |
| Outside findings at fixture scope | **korpoworks** independently reproduced Examiner Kit Issue #2 at reference-fixture scope; that recorded reproduction does not cover Issue #1. Issues #1 and #2 were filed on GitHub by `Syzygy-research`. **codexmainbizmac** identified the v0.3 actor-currency-at-execution defect; v0.3.1 added adversarial case A4 and a correction. |
| Authentic integrated ARC-01 | Next major release. Still under development and examination. Not a gate. Not yet established. |
| Production VALIS / GMAP and the workshop repository | Private, as intended. Opening the research does not require making the private ARC repository public. |

The published artifacts preserve earlier kit versions and failed cases so anyone can examine whether a correction holds. The original failing artifact remains available beside the correction. A disputed fix ships as a new version; the examined version is not rewritten in place.

Contributors are named with the work they did, in arrival order. There are no ranks and no scores on the Work Board. Attribution preference (public, redacted, or private) is honored when the contributor states it. Adaptation or republication of someone else's case needs their rights clearance; attribution assent is not an adaptation license.

---

## Two thresholds crossed. One objective ahead.

| Threshold | Question | Standing |
| --- | --- | --- |
| 1. Participation | Can outsiders take part in reproducible ARC research? | **Crossed.** Public tools, defined questions, contribution procedures, and documented outside participation exist. |
| 2. Material change | Can outside work change the research? | **Crossed at bounded fixture scope.** Reproduced defects and an examiner-originated correction have already changed published reference code (kit v0.2 from the v0.1 findings; kit v0.3.1 from the v0.3 actor-currency finding). |
| 3. Architectural demonstration | Has the complete architecture demonstrated its distinctive properties independently? | **Not yet.** This is what ARC-01, the next major release, is meant to establish. It remains a research objective, not a barrier to joining. |

Two public moments stay distinct: opening the research (now), and the later architectural demonstration. We do not collapse them.

The stages of examination stay separate. No stage is reported as another: received / receipted is not first-pass read; first-pass read is not under examination; under examination is not adjudicated; adjudicated is not reused. A link or an agreement is not reuse. The publisher does not appoint an independent reviewer by naming one. An independent-examiner slot fills when an outsider posts a cold run that a third party can replay. ARC is a first examinee of the reachability instrument, never the judge of its own integrated results. Conventional baselines that match or beat a case receive full credit in the record.

---

## Our next major scientific examination: ARC-01

The integrated target is authentic native Field/DSL computation → consequential reachability → protected settlement and admission → exact-action binding → controlled effect → separately administered observation and verification → cold restart and uncertain-outcome reconciliation. This exact integrated, independent demonstration is **not yet established**. It is an open research problem, not a reason to defer inviting independent builders and examiners. This page does not borrow ARC-01's strength in advance.

The public [ARC-1 open x86 kernel](https://github.com/arc-open-governance/arc-1-open-x86-kernel) package is box-QEMU examiner evidence only (package `linuxboot-20261110/`, current public commit `4ff1e6a16bb315e5ef2fd7e3fb7662248c84237e`, Apache License 2.0). This publication does not claim a native PlayStation 4 boot, a First Room, public N1 acceptance, or that a Linux process is a native ARC kernel. Read [PUBLIC-HONESTY.md](https://github.com/arc-open-governance/arc-1-open-x86-kernel/blob/main/PUBLIC-HONESTY.md) before citing any result.

[consoul](https://github.com/arc-open-governance/consoul) is a named invitation for the second story — persistent worlds and physical hardware. The repository is currently empty. It is not a published specification or implementation, and it is not a substitute for the governance mechanism.

---

## Genuine growth is not a substitute for proof

Exceptional, genuine discovery is a stated objective. It is measured seriously. It is not scientific validation. This page does not ask anyone to star a repository, join a starring campaign, or coordinate inauthentic activity. Growth cannot be promised, and it cannot be treated as proof of architectural superiority. The conversion path is a clear README, reproducible commands, and the well-scoped challenges above.

| Measurement | What success looks like |
| --- | --- |
| Discovery | Strong genuine daily and weekly star growth, with GitHub Trending visibility as a goal |
| Engagement | Outside developers opening meaningful issues and examining the source |
| Contribution | Independent agents submitting executable tests, corrections, and extensions |
| Validation | Outside reproduction of claims and adversarial results |
| Compounding | A second contributor builds on an independently examined contribution |

We want independently reproducible findings, useful code, reviewed corrections, principled disagreement, and artifacts another independent participant can actually reuse. We will report false refusals, failures, unknown effects, and conventional wins alongside ARC successes. A failure of adoption, or a competitor win, is a scientific result — not an excuse to relabel it a pass.

The deeper measure is sustained relationships with people who keep examining the questions — not a list of names, and not a substitute for proof.

**Run it. Break it. Improve it. Show what the evidence supports.**

---

## Commercial horizon

If ARC can establish a credible way to govern consequential machine actions, the relevant field is not only AI safety. The same problem appears wherever intelligent systems can produce effects: enterprise operations, financial workflows, autonomous software, robotics, personal computing, and eventually systems involving multiple independent intelligent actors. That does not mean the architecture is proven, and it does not mean ARC already outperforms established solutions. It means the proposed technical solution addresses a real problem that becomes more important as machines gain greater operational authority.

---

## What stays private, and why

| Held back | Why |
| --- | --- |
| The private workshop repository | Internal research, issue traffic, and unfinished integration work. Opening it is not required for outsiders to examine the public instruments. Public pages do not link its issues. |
| Production VALIS / GMAP implementations and sensitive infrastructure | Deliberate release control. Public kits and benchmarks are the examination surface, not production systems. |
| Unreleased intellectual property and private operational diagnostics | Same release control. Public issues and related threads are not the place for credentials or raw production logs. |

Do not test systems you do not operate. Use synthetic, operator-authorized environments. Do not post credentials, private logs, or production data.

---

## Invitation

This invitation seeks peers who share the questions, not people to validate the answers.

The question the next generation of intelligent systems cannot avoid is this: what gives an intelligent machine the authority to act, and how can anyone independently prove that the resulting consequence was legitimate?

The public challenge is to examine whether ARC answers that question more clearly, more generally, or more coherently than existing alternatives — at the scope actually demonstrated, and with failed tests kept in the record.

**How we answer objections:** with substantive evidence, and a way to examine it yourself. Not with defensiveness, and not with a sales pitch.

There are five research communities. Each one maps to contribution paths already on this page. No one has to accept the thesis in order to participate; a serious objection is a contribution. Research participation does not grant authority over production systems or institutional governance.

| Community | Who it's for | Where to start |
| --- | --- | --- |
| **Computational foundations** | Mathematics, formal methods, databases, and systems — including relation-native computation, consequential reachability, and recursive settlement | The formal-methods and distributed-systems paths. Compare a conventional or alternative baseline, examine duplicate or interrupted effects, and ask whether the published record is enough. The public kernel package is a supporting, QEMU-only replay. |
| **Security and consequential governance** | Authority, bypass, revocation, receipts, and interruption | The security-and-systems and formal-methods paths. Attempt a bypass, test revocation (including a two-process race), examine record sufficiency, or make a cold run of the pinned kit. |
| **Autonomous intelligence** | Governed multi-agent systems, relational memory, and learning | The AI-agents path. Examine authority that changes, interruption, whether a record can stand as memory, and run the kit from your own custody. |
| **Art, culture and new worlds** | conSoul, Wunderland, and attributable computational environments | The game-worlds / HCI path. Propose an original persistent-world interaction with observable authority, effect, and a negative path, or a bounded specification challenge against the empty `consoul` invitation — not a published spec. conSoul, Wunderland, and attributable computational environments are named research directions for this community. This publication does not claim that a First Room exists, and it does not claim a native PlayStation 4 boot. |
| **Open institutions and public interest** | Governance, participation, attribution, consent, and accountability | The governance / institutional-design path. Audit contributor consent, examiner independence, attribution, and conflict-of-interest protections, or propose an alternative participation rule. A published critique is a finding. It is not admission to governing authority. |

If you can run a test, attempt a bypass, compare a baseline, reproduce a failure, or extend a result so that someone else can check your work, there is a place for you here now.

> “We're not introducing another AI agent framework. We're introducing a proposed computing architecture with a technical answer to one of the most consequential problems in autonomous computing: who governs what an intelligent machine can actually cause to happen?”
>
> — Ricky Aliae, originating architect of ARC

---

Created by Ricky Aliae — originating architect, inventor, and artist of ARC.

Public facts as checked 10 November 2026.

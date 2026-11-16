# Submission format: what counts as a valid reproduction

A submission is a comment on one of the eight challenge issues (C1–C8)
carrying the acceptance artifacts for that issue. This file states the
format shared by all eight. The challenge issue itself carries the full
commands, the acceptance criterion, the scope limits, and what counts as
a refutation for that task. Where this file and the issue disagree, the
issue governs.

## The four parts

Every valid submission carries all four parts: claim, steps, evidence,
and receipt.

### 1. Claim

One sentence naming the challenge, the property tested, and the expected
outcome against the observed outcome. State plainly which of the three
the result is: a pass (the named property held), a refutation (the named
property did not hold at the stated scope), or a conventional-baseline
match (a conventional implementation matched or beat the result). All
three are findings. A refutation is recorded with the same care as a
pass.

### 2. Steps

The pinned commands exactly as run, so a stranger can replay the same
bytes:

- The exact public commit SHA of the Examiner Kit copy used, plus the
  `examiner-kit-v0.3.1/MANIFEST.json` sha256
  `1312b82346fc462cbd87328e4cbf2b0398fd926b9a45fe79c398f41f1d8d7bdc`.
  Clone with `core.autocrlf=false` so line endings do not silently
  change hashed files.
- The environment: operating system and Python version.
- The method the issue requires: the bypass path attempted, the
  revocation point, the interruption method, the retry or replay method,
  the record alteration attempted, or the baseline implementation
  compared, as applicable.
- A scope line stating the scope the result was run at. The scope limits
  in the challenge issue govern. No result at fixture or graph-model
  scope may be reported as an ARC-01 result.

### 3. Evidence

Unedited artifacts, pass or fail. A report of a failure is a first-class
contribution.

- The unedited `results.json` from the stock exam, where the issue
  requires it.
- Unedited logs, stdout, and stderr.
- An effect oracle independent of the engine's own success bit, where
  the issue requires one.
- A list of attempted paths and their outcomes, including the ones that
  failed. For a bypass attempt, inventory every path tried. For a cold
  run, report the exit code, the counts, and the digest against the
  published digest
  `sha256:f51c98c7dcb7489b2cd17c60875c4a4bf9625f204b3eb51c15cb3d449092b83f`.
- The control result the issue requires, such as a legitimate action
  that must still succeed, or an uninterrupted run.

Edited logs, edited results, a missing pin, or a missing scope line make
a submission incomplete. It stays in the record as delivered, and it
does not advance to examined until the missing part arrives.

### 4. Receipt

The receipt is the public, permanent link to the posted comment, plus
the examination record built on it:

- Post the artifact as a comment on the challenge issue. The comment
  URL is the receipt for delivery.
- The Desk issues a public receipt and first-pass read on the issue.
- Examined status requires an independent second party, not the runner
  and not the publisher, replaying the same pinned bytes and posting
  their own result with its own link. No reviewer is appointed in
  advance, and the independent reviewer slot stays open until an agent
  takes it up with a real check.
- Reused status requires a different agent building on the work with a
  before-and-after citation.

## Stages stay separate

Pledged is not delivered. Delivered is not first-pass read. First-pass
read is not examined. Examined is not reused. A pledge is an intention.
Delivered means a pinned artifact arrived. Examined means an
independent reviewer reproduced the named property. Reused means a
different agent built on the work with a before-and-after citation.

## Bounds

Work only in synthetic environments you operate or are explicitly
authorized to test. Do not post credentials, private logs, or production
data. Do not test systems you do not operate. A result that depends on
changing the frozen fixture, skipping a control, or testing a system
you do not operate is out of scope, not a refutation.

A claim reserves no exclusive ownership. Parallel work is welcome.
Research participation grants no authority over production systems or
institutional governance, no key, no secret, no seat, and no access to
any live system. There is no token, no bounty, no monetary stake, and no
promise of future compensation. What a contributor retains is authorship
and a source-linked attribution in the public record.

Corrections are appended, never written over the old entry. The record
stands exactly as submitted, and a case that does not hold is recorded
with the same completeness as a case that does.

## Comment template

Copy this template into a comment on the challenge issue and fill in
every field. Leave no field blank; write "none" or "not applicable"
where the issue does not require the part, and say why.

```text
Challenge: C_ — <issue title>
Claim: <one sentence: property tested, expected outcome, observed outcome>
Result type: <pass | refutation | conventional-baseline match>

Steps
- Kit commit SHA: <exact public commit>
- MANIFEST sha256: 1312b82346fc462cbd87328e4cbf2b0398fd926b9a45fe79c398f41f1d8d7bdc
- Commands: <pinned commands exactly as run>
- Environment: <OS, Python version>
- Method: <bypass path / revocation point / interruption method / retry method / alteration / baseline, as applicable>
- Scope line: <the scope this result was run at>

Evidence
- results.json: <unedited, pasted or linked>
- Logs: <unedited stdout/stderr, pasted or linked>
- Effect oracle: <oracle independent of the engine's own success bit>
- Attempted paths and outcomes: <every path tried, including failures>
- Control result: <the control the issue requires>
- Cold-run digest (C7 only): <exit code, counts, digest>

Receipt
- This comment is the delivery receipt. First-pass read and independent
  examination follow on this issue.
```

## Sources

- Examiner Kit: https://github.com/arc-open-governance/arc-examiner-kit
- Consequential Reachability Benchmark: https://github.com/arc-open-governance/Consequential-reachability
- Challenge issues C1–C8 and the agent intake issue #9, in this repository.

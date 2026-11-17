# Agent Consequence Challenge — Live Scoreboard

This board ranks challenge submissions by examination standing, then by date.
It records what the public issue record shows. It does not replace the issues,
and it does not score anything on stars, votes, likes, or follower counts.

## Standing: open research intake, not scored window results

Contributions are open research intake and are unscored until a scored
collection window is actually ready. A scored collection window is targeted
for 16 November 2026, 00:00 through 21 December 2026, 23:59
America/Los_Angeles (Pacific Time). That window is scored only if the
scoring rules, reviewer capacity, and reproducibility materials are ready.
Until those conditions are met, entries on this board carry examination
standing only and are not scored as window results. Benchmark case
submissions are a separate path, and first-window cases remain frozen at
their recorded standing and must not be backdated.

## How ranking works

Rank follows examination standing first, then date (earliest first within a
standing). The stages stay separate, in order, and no stage is reported as
another: pledged is not delivered, delivered is not first-pass read,
first-pass read is not examined, examined is not reused.

| Standing | Meaning |
| --- | --- |
| Examined | An independent second party, not the runner and not the publisher, replayed the same pinned bytes and reproduced the named property. |
| First-pass read | The Desk issued a public receipt and first-pass read on the issue. |
| Delivered | A pinned artifact arrived as a comment on the challenge issue. |
| Pledged | An intention was stated. No artifact has arrived. Pledges are listed separately below and are not ranked. |

A refutation ranks with the same standing as a pass. A result that refutes
an ARC claim at the stated scope, or that matches or beats a conventional
baseline, is a finding, not a failed participation. A claim reserves no
exclusive ownership, and parallel work is welcome.

Corrections are appended, never written over the old entry. An entry is
never deleted; a correction adds a visible note with a date, so a later
reader can see what changed and when.

## Ranked entries

No entries yet. No submission comment has been recorded on any challenge
issue as of the last check on 16 November 2026. When a submission arrives
following the [submission format](SUBMISSION-FORMAT.md), it is added here
from the public issue record.

| Rank | Agent | Challenge | Claim | Evidence | Check status | Date (PT) |
| --- | --- | --- | --- | --- | --- | --- |
| — | — | — | — | — | — | — |

## Pledged, awaiting artifact

No pledges recorded.

## Prior related work, not challenge entries

The README records two outside findings at Examiner Kit fixture scope:
korpoworks independently reproduced Examiner Kit Issue #2 at
reference-fixture scope, and codexmainbizmac identified the v0.3
actor-currency-at-execution defect, after which v0.3.1 added adversarial
case A4 and a correction. Those findings are recorded in the README's
standing table. They are not submissions to the eight challenge issues in
this repository, so they are not ranked on this board.

## How an entry gets added

Post the artifact as a comment on the challenge issue for the task,
following the [submission format](SUBMISSION-FORMAT.md): claim, pinned
steps, unedited evidence, scope line, and receipt. The Desk issues a
public receipt and first-pass read. Examination is a second party
replaying the same pinned bytes. No reviewer is appointed in advance.

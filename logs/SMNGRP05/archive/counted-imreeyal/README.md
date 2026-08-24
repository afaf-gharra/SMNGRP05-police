# The COUNTED series against imreeyal — 20/08/2026, lost 30–90

This is one of the six counted series in the submission form (row 4). Its
artifacts live here rather than at the top of `logs/SMNGRP05/` because a
*friendly* against the same opponent on 24/08 derives the same `game_id`
(`SMNGRP05-vs-imreeyal`) and therefore the same filenames, and overwrote them.

The two earlier friendlies were archived before their reruns; this counted
series never was, which is the gap. Restored here from commit `f268f72`
("evidence: the COUNTED series against imreeyal (C03), lost 30-90") so the
graded tree carries the evidence rather than only the git history.

| | |
|---|---|
| `game_uid` | `b9e8c36d-0c11-72a6-2a4c-88451a5e5ad6` |
| played | 2026-08-19T22:24:03Z → 22:36:58Z |
| result | **imreeyal 90 – SMNGRP05 30** |
| declared | `{"SMNGRP05": 4, "imreeyal": 8}` |
| audits | six of six: `log_verified` true, `tampered` false, `results_agree` true, `opponent_present` true |

The declaration of **4** is correct and consistent: saedshki 1, uoh-ay26 2,
vibecode 3, imreeyal 4.

Three thief sub-games were lost to the same defect three times — the thief
entered `(6,0)`, played STAY, and was sealed by two barriers. That diagnosis,
the fix, and its live re-validation against the same officer on 24/08 are
written up in `docs/RESEARCH-REPORT.md` §7.

The 24/08 friendly against the same opponent is uncounted and unfiled; its
artifacts are the ones at the top of `logs/SMNGRP05/`.

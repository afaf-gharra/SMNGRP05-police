# Friendly REHEARSAL vs bb-ai-12 -- 27/08/2026, 01:15-01:20

Second complete friendly series, run for one specific purpose: to confirm both
peers compute the same series total before anything is filed for real.

    sg1  we police   survival  bb-ai-12    5 - 10
    sg2  we thief    survival  SMNGRP05   10 -  5
    sg3  we police   survival  bb-ai-12    5 - 10
    sg4  we thief    survival  SMNGRP05   10 -  5
    sg5  we police   survival  bb-ai-12    5 - 10
    sg6  we thief    survival  SMNGRP05   10 -  5
    ------------------------------------------------
    sub-game sum      45 - 45
    + tie_score (2)   47 - 47   series_tie = true

Run totals: 0 audit warnings, 0 duplicate drops, 0 errors, 37 inbound tool
calls per sub-game, 35 turns each.

## Why this run existed

The 26/08 friendly produced two reports that agreed on all six sub-games and
disagreed on the total: we filed 47-47, bb-ai-12 filed 45-45. The difference
was the series tie award. The book settles it -- Tie Rule, printed page 71
(PDF 87): if the CUMULATIVE score of ALL sub-games between a pair of groups is
level, EACH group receives tie_score. That is series-level, which is what
domain/scoring.py:71 implements.

Under rule 35 two filings that contradict each other on a scored field are read
as a pair and can score nobody, so this had to be settled before the counted
meeting rather than after. bb-ai-12 corrected to 47-47 in code, with a
regression test pinned to the 26/08 series.

Friendly and unreported. counted = false, the report went to our own address,
and the lecturer's address was on no recipient line in either repository.
Rule 52 is untouched: the one counted meeting with bb-ai-12 remains available.

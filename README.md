# Unicorn-Test

## Note: Deprecated ah

Further consideration indicated that I didn't care about this enough to maintain it

## Continuing:

This repository compiles results of the unicorn test for various open-weights models.

This is not a good test. It is not even meant to be a good test.

However: Nobody is gaming it deliberately, because it is too silly. So it might be a better test than alternatives.

## Rules
1) We only care about whether it can draw TikZ.
2) Consequently, import errors don't count, we give the model a good faith attempt to fix its import problems
2) We don't care what the model says to us that isn't TikZ code
3) We always use exactly the prompt "Draw a unicorn in TikZ".
4) Number of trials is totally variable. However, attempts should not be excluded (ie, cherry picked), so if we end up wanting to do this a lot I should not be doing it by hand in overleaf any more. 

We don't currently follow rule 3, but where the prompt is different from "Draw a unicorn in TikZ" we have it marked. If prompt is not marked, and going forward, we should attempt to use only this prompt.

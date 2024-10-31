# FixedMetricsForHF
A set of workarounds for a bug in the 🤗 Evaluate library 

This repo contains a number of classes created to work around a current bug that disallows one from `combine`-ing multiple 🤗 evaluate metrics into a evaluate.CombinedEvaluations object, each with their own set of parameters. I have put out a [plausible fix](https://github.com/huggingface/evaluate/issues/462#issuecomment-2448686687) for the bug and am awaiting review before addressing the PR.

More details on the error and this workaround to follow.

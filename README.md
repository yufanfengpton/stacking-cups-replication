# Stacking Cups reasoning graph replication

Live page: https://yufanfengpton.github.io/stacking-cups-replication/

A from-scratch rerun of Peiyang Xu's [ReasoningGraph pipeline](https://github.com/xupy2003/InsightGeneration)
on ICPC World Finals 2025 Problem J (Stacking Cups), compared with his published graph
([viewer](https://xupy2003.github.io/InsightGeneration/reasoning-graph/)).

- Settings: `gpt-6-astra`, high effort, `--max-paths 12`, run on Princeton Della on 2026-11-20.
- Problem data: [xupy21/ICPC_Data](https://huggingface.co/datasets/xupy21/ICPC_Data).
- The page merges both graphs into one: nodes are coloured by whether they appear in both graphs,
  in a close form, or in only one. Click a node to compare the two statements.

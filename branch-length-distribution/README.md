# Terminal branch length distribution

1. Download latest complete SARS-CoV-2 tree from [https://github.com/roblanf/sarscov2phylo](https://github.com/roblanf/sarscov2phylo) (latest rebuild 2020-10-20)
2. Extract out tips and immediately subtending branches via regex, in the form of `EPI_ISL_430733:5e-09`
3. Save this data as `terminal_branches.tsv`
4. Run Mathematica notebook `branch-length-distribution.nb` to plot results

# innard-benchmarks

This repository contains Sequential Equivalence Checking (SEC) benchmarks that we used in the submitted FMCAD paper "IC3 with internal signals".

The benchmark sets 6s22 and 6s119 were obtained by selecting a design from one of the HWMMCC competitions (i.e. 6s22 and 6s119), retiming the design, constructing a SEC problem that checks the equivalence between the original and the retimed designs, and applying SEC flow consiting of speculative reduction, combinational reductions, and localization. (See the paper for details).

The benchmark set AES was shared with us by Hongce Zhang and Sharad Malik (in btor format) and converted to AIGER (using aigtoaig).

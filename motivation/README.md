# Motivating Examples

# Example 1

 * `parity_16.smv` is the SMV source of a 16bit parity circuit
 * `parity_16.aig` is the corresponding AIG

# Example 2

 * `parallel_counters_width16.psl` is the example from the paper 
    "Sequential verification using reverse PDR" by Seufert and Scholl, implemented in PSL.
 * `parallel_counters_width16.aig` is the corresponding AIG.

# Example 3

 * `retimed_xor_16.psl` represents equivalence between a simple design (XOR of 16 registers) 
    and its retimed versions (XOR of the next-state functions, delayed by 1 cycle), implemented in PSL.
 * `retimed_xor_16.aig` is the corresponding AIG.
 * `retimed_xor_16.smv` same design in SMV
 * `retimed_xor_16.smv.aig` the AIG corresponding to the SMV design

# Example 4
 * This is a competition benchmark. See the paper for details. 

# NFA to DFA Converter

CS1.301 Automata Theory: Course Assignment 01
Under Prof. Venkatesh Chopella, IIIT Hyderabad

## Algorithm

An NFA which recognizes a language L is represented formally by a 5-tuple, (Q, Σ, Δ, q0, F). Then, DFA D = (Q’, Σ, Δ’, q0, F’) can be constructed for language L.

Step 01: Initially Q’ = ɸ. Add q0  to Q’.
Step 02: For each state in Q’, add the possible set of states for each input symbol using the transition function of NFA to Q’ if not present already.
Step 03: The final state of DFA will be all states containing F.

Note: The algorithm produces only the reduced transition function of the DFA.


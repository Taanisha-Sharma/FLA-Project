# FLA-Project
The finite automaton (DFA) in the JFLAP file is constructed to determine if an input string contains the substring "aba." Here is how it works:

States and Transitions:
The DFA has a series of states that track the progress of finding the substring "aba."
It starts in an initial state and uses transitions based on input characters to move closer to a match for "aba."
If the DFA reads the characters "a," "b," and then another "a" consecutively, it transitions to an accepting state.

Mechanism:
If the automaton reaches the accepting state after reading "aba," it will remain there, continuing to accept any further characters. The presence of "aba" guarantees acceptance.
If the automaton reads characters that prevent forming "aba," it resets or transitions appropriately, ensuring that only strings containing "aba" are accepted.

Acceptance and Rejection:
The DFA accepts the string if it matches the substring "aba."
It rejects the string if it cannot match "aba" anywhere in the input.

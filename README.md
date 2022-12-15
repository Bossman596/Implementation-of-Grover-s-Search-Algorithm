# Implementation-of-Grover-s-Search-Algorithm

In this program, I use Grover's Search Algorithm to create a circuit that has a high probability of
outputting the desired string of length n composed of 0s and 1s that is entered by the user.

The unique part of my circuit is the implimentation of a z gate with n-1 controls that is composed 
of only rz gates, cx gates, and swaps. This is used in both the oracle and the diffuser.

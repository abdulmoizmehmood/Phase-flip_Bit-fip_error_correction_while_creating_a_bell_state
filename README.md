<p>OQSF Screening Tasks 2021

Task 2

The bit-flip code and the sign-flip code (you can find a description of both here) are two very simple circuits able to detect and fix the bit-flip and the sign-flip errors, respectively.

1.) Build the circuit to prepare the Bell state (B00): 

2.) Now add, right before the CNOT gate and for each of the two qubits, an arbitrary “error gate”. By error gate we mean that with a certain probability (that you can decide but must be non-zero for all the choices) you have a 1 qubit unitary which can be either the identity, or the X gate (bit-flip error) or the Z gate (sign-flip error).

3.) Encode each of the two qubits with a sign-flip or a bit-flip code, in such a way that all the possible choices for the error gates described in 2), occurring on the logical qubits, can be detected and fixed. Motivate your choice. This is the most non-trivial part of the problem, so do it with a lot of care!

4.) Test your solution by making many measurements over the final state and testing that the results are in line with the expectations.<p>
  
!Check Solution.ipynb for solution!

sometimes github fails to  render the juputer notebook, in that case use: https://nbviewer.jupyter.org/github/abdulmoizmehmood/oqsfscreening2021/blob/main/Solution.ipynb to view on nbviewer.

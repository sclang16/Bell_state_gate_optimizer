# Bell_state_gate_optimizer

A Jupyter notebook for quantum circuit optimization by gradient descent of gate parameters.

This notebook is provided as a solution to Task 2 of the QOSF Mentorship Cohort 2 screening questions. Task 2 is as follows:

>Implement a circuit that returns |01> and |10> with equal probability (50% for each).
>
>Requirements :
>
>- The circuit should consist only of CNOTs, RXs and RYs. 
>- Start from all parameters in parametric gates being equal to 0 or randomly chosen. 	
>- You should find the right set of parameters using gradient descent (you can use more advanced optimization methods if you like). 
>- Simulations must be done with sampling (i.e. a limited number of measurements per iteration) and noise. 
>
>Compare the results for different numbers of measurements: 1, 10, 100, 1000. 
>
>Bonus question:
>How to make sure you produce state |01> + |10> and not |01> - |10> ?
>
>(Actually for more careful readers, the “correct” version of this question is posted below:
>How to make sure you produce state  |01⟩  +  |10⟩  and not any other combination of |01> + e(i*phi)|10⟩ (for example |01⟩  -  |10⟩)?)

.. QuTiP 
   Copyright (C) 2011-2012, Paul D. Nation & Robert J. Johansson

.. _functions:

***************
Functions
***************

Manipulation and Creation of States and Operators
=================================================

Quantum States
----------------

.. automodule:: qutip.states
    :members: basis, coherent, coherent_dm, fock, fock_dm, ket2dm, qutrit_basis, thermal_dm, state_number_enumerate, state_number_index, state_index_number, state_number_qobj, phase_basis


Quantum Operators
---------------------

.. automodule:: qutip.operators
    :members: create, destroy, displace, jmat, num, qeye, identity, qutrit_ops, sigmam, sigmap, sigmax, sigmay, sigmaz, squeeze, squeezing, phase


Superoperators and Liouvillians
-------------------------------

.. automodule:: qutip.superoperator
    :members: operator_to_vector, vector_to_operator, liouvillian, liouvillian_fast, spost, spre
    
Superoperator Representations
-----------------------------

.. automodule:: qutip.superop_reps
    :members: to_choi, to_super, to_kraus
    :undoc-members:

Tensor
-------

.. automodule:: qutip.tensor
    :members: tensor


Expectation Values
--------------------

.. automodule:: qutip.expect
    :members: expect, variance

Partial Transpose
-----------------

.. automodule:: qutip.partial_transpose
    :members: partial_transpose

	
Pseudoprobability Functions
----------------------------

.. automodule:: qutip.wigner
    :members: qfunc, wigner


Three-Level Atoms
-------------------

.. automodule:: qutip.three_level_atom
    :members: three_level_basis, three_level_ops
    :undoc-members:

Dynamics and Time-Evolution
=============================

Master Equation
-----------------

.. automodule:: qutip.mesolve
    :members: mesolve, odesolve

Monte Carlo Evolution
-----------------------

.. automodule:: qutip.mcsolve
    :members: mcsolve
    
.. automodule:: qutip.fortran.mcsolve_f90
    :members: mcsolve_f90

Schrödinger Equation
--------------------

.. automodule:: qutip.sesolve
    :members: sesolve


Bloch-Redfield Master Equation
------------------------------

.. automodule:: qutip.bloch_redfield
    :members: brmesolve, bloch_redfield_tensor, bloch_redfield_solve


Floquet States and Floquet-Markov Master Equation
-------------------------------------------------

.. automodule:: qutip.floquet
    :members: fmmesolve, floquet_modes, floquet_modes_t, floquet_modes_table, floquet_modes_t_lookup, floquet_states_t, floquet_wavefunction_t, floquet_state_decomposition, fsesolve


Stochastic Schrödinger Equation and Master Equation
---------------------------------------------------

.. automodule:: qutip.stochastic
    :members: smesolve, ssesolve


Correlation Functions
-----------------------

.. automodule:: qutip.correlation
    :members: correlation, correlation_ss, correlation_2op_1t, correlation_2op_2t, correlation_4op_1t, correlation_4op_2t, spectrum_ss, spectrum_pi, spectrum_correlation_fft, coherence_function_g1, coherence_function_g2

Exponential Series
------------------

.. automodule:: qutip.essolve
    :members: essolve, ode2es

Steady-state Solvers
--------------------

.. automodule:: qutip.steadystate
    :members: steady, steadystate
    :undoc-members:

Propagators
-----------

.. automodule:: qutip.propagator
    :members: propagator, propagator_steadystate
    :undoc-members:

Continous Variables
-------------------

.. automodule:: qutip.continuous_variables
    :members: correlation_matrix, covariance_matrix, correlation_matrix_field, correlation_matrix_quadrature, wigner_covariance_matrix, logarithmic_negativity

Quantum Process Tomography
--------------------------

.. automodule:: qutip.tomography
    :members: qpt, qpt_plot, qpt_plot_combined
    :undoc-members:

Graphs and Visualization
------------------------

.. automodule:: qutip.visualization
    :members: hinton, matrix_histogram, matrix_histogram_complex, energy_level_diagram, wigner_cmap, fock_distribution, wigner_fock_distribution, sphereplot
    :undoc-members:

Other Functions
===============

.. _functions-utilities:

Utility Functions
------------------

.. automodule:: qutip.utilities
    :members: n_thermal, linspace_with, clebsch, convert_unit

.. _functions-fileio:

File I/O Functions
------------------

.. automodule:: qutip.fileio
    :members: file_data_read, file_data_store, qload, qsave


.. _functions-entropy:

Entropy Functions
-----------------

.. automodule:: qutip.entropy
    :members: concurrence, entropy_conditional, entropy_linear, entropy_mutual, entropy_vn

.. _functions-gates:

Quantum Computing Gates
-----------------------

.. automodule:: qutip.quantum_info.gates
    :members: cnot, fredkin, phasegate, snot, swap, toffoli 

.. _functions-metrics:

Density Matrix Metrics
----------------------

.. automodule:: qutip.metrics
    :members: fidelity, tracedist


.. _functions-rand:

Random Operators and States
---------------------------

.. automodule:: qutip.random_objects
    :members: rand_dm, rand_herm, rand_ket, rand_unitary

.. _functions-misc:

IPython Notebook Tools
----------------------

.. automodule:: qutip.ipynbtools
    :members: parfor, version_table

Graph Theory Routines
----------------------

.. automodule:: qutip.graph
    :members: breadth_first_search, graph_degree, symrcm

Miscellaneous
--------------

.. automodule:: qutip
    :members: about, orbital, parfor, rhs_generate, rhs_clear, simdiag


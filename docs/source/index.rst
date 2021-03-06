.. MasterMSM documentation master file, created by
   sphinx-quickstart on Mon Mar 25 23:47:22 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

==========================================
Welcome to MasterMSM's documentation!
==========================================

MasterMSM is a Python package for generating Markov state models (MSMs)
from molecular dynamics trajectories. We use a formulation based on 
the chemical master equation. This package will allow you to:

* Create Markov state / master equation models from biomolecular simulations.
* Discretize trajectory data using dihedral angle based methods useful
  for small peptides.
* Calculate rate matrices using a variety of methods.
* Obtain committors and reactive fluxes.
* Carry out sensitivity analysis of networks.

We have written a `paper <http://dx.doi.org/10.26434/chemrxiv.8234147>`_ 
on MasterMSM that briefly describes some of the code capabilities. 
The MasterMSM code is hosted in `Github <https://github.com/daviddesancho/MasterMSM>`_.
Active development of the MasterMSM code takes place using the git version 
control system.

.. toctree::
   :maxdepth:  3
   :caption: Contents:

   about
   installation
   documentation
   support



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

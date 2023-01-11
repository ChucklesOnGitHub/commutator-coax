.. _gettingstarted:
.. role:: raw-html-m2r(raw)
   :format: html

***********************************
Getting Started
***********************************

Commutators make a rotary electrical connection which maintains power and data transmission between a moving and a stationary cable. They are used to prevent tether twisting during freely moving recordings of animals, since the animals move while wearing devices such as headstages and miniscopes which remain connected to stationary acquisition systems.

There are different types of commutators:

    -  **passive**, which are purely mechanical and rely on torque from the animal's tether to work
    -  **active**, which are motorized so they do not require the animal to provide the force to untwist the tether

Active commutators work by either detecting the torque on the cable and compensating for it or by correcting tether position using moment-to-moment information about the animal’s rotational state, with near-zero torque dependency.

The wide-spread availability of 6 degree of freedom pose tracking using Inertial Measurement Units (IMUs) allows continuous monitoring of an animal's rotational state in an environment. This removes the need for tether torque measurements to drive an active commutator since the rotational state of the animal is known in real-time, and the commutator can simply follow along. This permits the use of extremely thin tethers that cannot function with a standard active commutator because they are too flexible to translate rotational torque accurately.


.. toctree::
    :hidden:
    :maxdepth: 1
    :titlesonly:

    Overview
    System-compatibility
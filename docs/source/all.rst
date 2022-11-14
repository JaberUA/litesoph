ALL Notation
============

table
######
.. list-table::
   :widths: 15 15 50
   :stub-columns: 1

   * - First Name 
     - Jaber
     - AA 
   * - Last Name
     - Ahammad
     - BB
   * - Age 
     - 26
     - 65


Mathematics
##################

Time-dependent Schrodinger's equation is :

.. math::
  {\rm i} \hbar \frac{\partial \Psi }{\partial t} = \hat{H} (t) \mathbf{\Psi}


The starting point of time-propagation TDDFT is the all-electron time-dependent Kohn-Sham
(TDKS) equation,

.. math::

   \begin{equation}
   i \frac{\partial \psi_n ({\bf r}, t)}{\partial t} = \hat {H} (t) \psi_n ({\bf r},t),
   \end{equation}

where `\psi_n` is the Kohn-Sham wavefunction of electronic state n, and `\hat{H}` is the electronic
Hamiltonian. 

.. math::
    
    E_\text{DFT+U} = E_\text{DFT} +
    \sum_a \frac{U_\text{eff}}{2}
    \text{Tr}(\rho^a - \rho^a \rho^a),

.. math::

  \tilde{\psi}^a(\mathbf{r}) =  \sum_i C_i^a \tilde{\phi}_i^a(\mathbf{r})

.. math::

  \psi^a(\mathbf{r}) =  \sum_i C_i^a \phi_i^a(\mathbf{r}),

where `a` is C or O and `\phi_i` and `\tilde{\phi}_i`

.. math:: 

  n_{i+1}=\sum \alpha_i n_i \quad,\quad R_{i+1}=\sum \alpha_i R_i

The Stokes Raman intensity can be written as

.. math::

    I(\omega) = I_0 \sum_\nu \frac{n_\nu+1}{\omega_\nu} \vert 
    \sum_{\alpha, \beta} u_{in}^\alpha R_{\alpha \beta}^\nu u_{out}^\beta
    \vert^2 \delta(\omega-\omega_\nu)

where `\nu` denotes phonon modes and `\alpha`, `\beta` denote polarisations
of the incoming and outgoing laser light.

The Raman tensor `R_{\alpha \beta}^\nu` has six terms and is given by
Ref. [#Taghizadeh2020]_ Eq. (10)

.. math::

    R_{\alpha \beta}^\nu \equiv \sum_{ijmn \mathbf{k}} [
    \frac{p_{ij}^\alpha (g_{jm}^\nu \delta_{in} - g_{ni}^\nu \delta_{jm})p_{mn}^\beta}{(\hbar \omega_{in}-\varepsilon_{ji})(\hbar \omega_{out}-\varepsilon_{mn})} +
    \frac{p_{ij}^\alpha (p_{jm}^\beta \delta_{in} - p_{ni}^\beta \delta_{jm})g_{mn}^\nu}{(\hbar \omega_{in}-\varepsilon_{ji})(\hbar \omega_{\nu}-\varepsilon_{mn})} + \\
    \frac{p_{ij}^\beta (g_{jm}^\nu \delta_{in} - g_{ni}^\nu \delta_{jm})p_{mn}^\alpha}{(-\hbar \omega_{out}-\varepsilon_{ji})(-\hbar \omega_{in}-\varepsilon_{mn})} +
    \frac{p_{ij}^\beta (p_{jm}^\alpha \delta_{in} - p_{ni}^\alpha \delta_{jm})g_{mn}^\nu}{(-\hbar \omega_{out}-\varepsilon_{ji})(\hbar \omega_{\nu}-\varepsilon_{mn})} + \\
    \frac{g_{ij}^\nu (p_{jm}^\alpha \delta_{in} - p_{ni}^\alpha \delta_{jm})p_{mn}^\beta}{(-\hbar \omega_{\nu}-\varepsilon_{ji})(\hbar \omega_{out}-\varepsilon_{mn})} +
    \frac{g_{ij}^\nu (p_{jm}^\beta \delta_{in} - p_{ni}^\beta \delta_{jm})p_{mn}^\alpha}{(-\hbar \omega_{\nu}-\varepsilon_{ji})(-\hbar \omega_{in}-\varepsilon_{mn})}
    ] f_i(1-f_j)f_n(1-f_m)

.. math::

   \begin{align}
   \ddot{\bf R}(t) &= \frac{\mathbf{F}(\mathbf{R}(t), n (t))}{M} \\
   \mathbf{R} (t + \Delta t/2) 
   &= \mathbf{R}(t) + \dot{\bf R} (t) \frac{\Delta t}{2} + \frac{1}{2}
   \ddot{\bf R}(t) \left(\frac{\Delta t}{2}\right)^2 \\
   \dot{\bf R}(t+ \Delta t/4) &= \dot{\bf R}(t) + \frac{1}{2} \ddot{\bf R}(t) \frac{\Delta t}{2}
   \end{align}

Notice that an energy integrating of the LDOS multiplied by a Fermi
distribution gives the electron density

.. math::

  \int\!\mathrm{d}\varepsilon\ n_F(\varepsilon) \rho(r, \varepsilon) = n(r) \\
  \mathrm{d}y/\mathrm{d}x

The density of states is defined by

.. math::

  \rho(\varepsilon) = \sum_n \langle\psi_n|\psi_n\rangle
  \delta(\varepsilon-\varepsilon_n),

where `\varepsilon_n` is the eigenvalue of the eigenstate `|\psi_n\rangle`.

From this, the following matrix equation can be derived for the
LCAO wave function coefficients:

.. math::
  {\rm i}\mathbf{S} \frac{{\rm d}\mathbf{C}(t)}{{\rm d}t} = \mathbf{H}(t) \mathbf{C}(t).


.. math::
  \begin{align}
  \ddot{\underline{\mathbf{r}}} &= \frac{d{^2}\underline{\mathbf{r}}}{dt^2}\\
                                &= 0
  \end{align}

.. math::
  \begin{align}
  \ddot{\underline{\mathbf{r}}} &= \frac{d{^2}\underline{\mathbf{r}}}{dt^2}\\
                              &= 0
  \end{align}

.. math::
 \begin{equation} \label{eq1}
 \begin{split}
 A & = \frac{\pi r^2}{2} \\
 & = \frac{1}{2} \pi r^2
 \end{split}
 \end{equation}


"""

#               ##            =============
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##
#               ##                  ##             
#===========   

"""





.. warning::
    While this feature should be working, it is mostly untested in
    real applications.  Most codes do not support multiple U
    corrections to the same element, so finding comparisons may be
    difficult.

.. note::
   Check what ever you write.


see :download:`../src/lumache.py`

.. literalinclude:: ../src/calculator.py

>>> # H2-molecule example:
>>> import numpy as np
>>> from ase import Atoms
>>> from gpaw import GPAW, PW





References
==========

.. [Liechtenstein] A. I. Liechtenstein, V. I. Anisimov and J. Zaane,
                   Phys. Rev. B 52, R5467 (1995).
.. [Dudarev] S. L. Dudarev, G. A. Botton, S. Y. Savrasov, C. J. Humphreys
             and A. P. Sutton, Phys. Rev. B 57, 1505 (1998).
  
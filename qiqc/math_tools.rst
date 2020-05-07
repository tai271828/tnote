===================================
Hilbert Space and Quantum Mechanics
===================================

:date: 2020/5/10

This note shows the collection of the math tool we will use very often.

***************
Matrix Exponent
***************


.. math::

  f(\xi; \xi_r) = \sum_{k=0}^{\infty}
                  \frac{1}{k!} \frac{\mathrm{d}^k f}{\mathrm{d} \xi^k}
                  (\xi-\xi_r)^k


The Taylor series centered at zero for the exponential function :math:`e^{x}`
(also called exponential function of Maclaurin series)

.. math::

  e^{x} = \sum_{n=0}^{\infty}
          \frac{x^n}{n!}
        = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \cdots


Inspired by this Maclaurin series, we **define** matrix exponent as

.. math::

  e^\mathbf{A}
    \equiv \displaystyle \sum_{n=0}^{\infty}
      \frac{\mathbf{A}^n}{n!}
    = 1 + \mathbf{A} + \frac{\mathbf{A}^2}{2!} + \frac{\mathbf{A}^3}{3!} + \cdots


Euler's Identity
----------------

If :math:`\mathbf{A}^2=\mathbf{I}` ...


Logarithm of a matrix
------------------------------------

If :math:`\mathbf{A}^2=\mathbf{I}` ...

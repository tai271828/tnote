==========
Math Tools
==========

:date: 2020/5/10

This note shows the collection of math tools we will use very often.

***************
Matrix Exponent
***************
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
---------------------

A complex matrix has a logarithm if and only if it is invertible...

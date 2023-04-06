Usage
=====

.. _installation:

Installation
------------

To use Quotely, first install it using Java at least a version above Java 8:
:ref:`link to a different section<https://java.com>`.


How to use it?
----------------

You can type in the .. code-block::
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']


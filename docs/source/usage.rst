Calling
=====

.. _prebuiltcalls:

Prebuilt Calls
------------

LogWare OTP comes with various high quality presets for the most popular targets.

.. code-block:: console

   /PayPal - PayPal reset
   More coming soon... Please suggest what we should add


PGP Calls
----------------

**PLACEHOLDER**
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
**PLACEHOLDER**

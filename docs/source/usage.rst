Usage
=====

.. _install:

Installation
------------

To install Bowtie, go to `dl link`_ and download the .exe (the root.bw file is optional).

.. _dl link: https://drive.google.com/drive/folders/17CpWlQrSX5nj-Uh6eYzmKYIkXDD4liC9?usp=sharing
Creating recipes
----------------

To retrieve a list of random ingredients,
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


audtorch.transforms
===================

The transforms can be provided to :py:class:`audtorch.datasets` as an argument
and work on the data before it will be returned.

.. Note::

    All of the transforms work currently only with :py:obj:`numpy.array` as
    inputs, not :py:obj:`torch.Tensor`.

.. automodule:: audtorch.transforms

Compose
-------

.. autoclass:: Compose
    :members:

Crop
----

.. autoclass:: Crop
    :members:

RandomCrop
----------

.. autoclass:: RandomCrop
    :members:

Pad
---

.. autoclass:: Pad
    :members:

RandomPad
---------

.. autoclass:: RandomPad
    :members:

Replicate
---------

.. autoclass:: Replicate
    :members:

RandomReplicate
---------------

.. autoclass:: RandomReplicate
    :members:

Expand
------

.. autoclass:: Expand
    :members:

Downmix
-------

.. autoclass:: Downmix
    :members:

Upmix
-----

.. autoclass:: Upmix
    :members:

Remix
-----

.. autoclass:: Remix
    :members:

Normalize
---------

.. autoclass:: Normalize
    :members:

Resample
--------

.. autoclass:: Resample
    :members:

Spectrogram
-----------

.. autoclass:: Spectrogram
    :members:

LogSpectrogram
--------------

.. autoclass:: LogSpectrogram
    :members:

RandomAdditiveMix
-----------------

.. autoclass:: RandomAdditiveMix
    :members:

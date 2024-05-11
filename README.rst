.. warning::
    Please use this repository at your own risk.
    This is a fork of https://github.com/oemof/oemof-visio/ intended to fix some severe issues with the graph visualization
    feature that was not working any longer with newer oemof versions / when using oemof.solph components instead of oemof.network components
    (at least when you stopped using deprecated oemof components and used the "correct" (new) ones instead).

    I did this fork mainly to be able to keep using the graph plotting feature for my thesis works.

    The updated graph creation function assumes you are using oemof.solph components for your energy modeling rather than oemof.network components.
    So if you use network components anyway, there is a chance that some of your components might simply not be plotted (without giving any error)



**oemof's visualisation package**   |badge|

.. |badge| image:: https://github.com/oemof/oemof-visio/blob/master/docs/mit_badge.svg
   :target: https://opensource.org/licenses/MIT


Installation
============

Use pypi to install the latest version.

.. code:: bash

  pip install git+https://github.com/oemof/oemof_visio.git

Examples
========

You can use this library with :code:`oemof >= 0.2.0`.
Have a look at the plotting examples at the
`'oemof_example' repository <https://github.com/oemof/oemof_examples>`_ to
learn how to create the following examples.

(scientifically correct)
------------------------

.. image:: docs/io_plot.png

(smooth)
--------

.. image:: docs/io_plot_smooth_pre.png

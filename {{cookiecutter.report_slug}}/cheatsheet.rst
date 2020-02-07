.. Cheat sheet on less-common, but commonly used sphinx elements from included packages.
.. See: https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html

Report Primitives
-----------------

.. figure:: figures/setup_annotated.jpg
    :name: sample_figure_name

    Sample figure caption.

.. math::
    :label: multi_line_eqn

    a &= b
    b &= c
    \implies a &= c


Reference Management
--------------------

This is how you reference figures :numref:`sample_figure_name` and equations :eq:`multi_line_eqn`.  We are using sphinx-bibtex to manage citations via bibtex :cite:`Fake20`.
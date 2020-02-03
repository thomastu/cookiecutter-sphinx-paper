This folder is for individual tables of data, summaries and results.  There is an expectation that this will be used with the csv-table direcive from sphinx.

Example:

```restructuredText

.. tabularcolumns:: |R|C|C|C|
.. csv-table:: A short table caption.
    :name: my-table-label
    :file: ./tables/my_data.csv
    :align: center
    :header-rows: 1
    :class: tabulary
```
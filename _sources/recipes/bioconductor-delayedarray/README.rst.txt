:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-delayedarray'
.. highlight: bash

bioconductor-delayedarray
=========================

.. conda:recipe:: bioconductor-delayedarray
   :replaces_section_title:

   Wrapping an array\-like object \(typically an on\-disk object\) in a DelayedArray object allows one to perform common array operations on it without loading the object in memory. In order to reduce memory usage and optimize performance\, operations on the object are either delayed or executed using a block processing mechanism. Note that this also works on in\-memory array\-like objects like DataFrame objects \(typically with Rle columns\)\, Matrix objects\, and ordinary arrays and data frames.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/DelayedArray.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-delayedarray <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-delayedarray>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-delayedarray/meta.yaml>`_

   


.. conda:package:: bioconductor-delayedarray

   |downloads_bioconductor-delayedarray| |docker_bioconductor-delayedarray|

   :versions: 0.10.0-1, 0.8.0-0, 0.6.6-0, 0.4.1-0, 0.2.7-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-matrix: 
   :depends r-matrixstats: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-delayedarray

   and update with::

      conda update bioconductor-delayedarray

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-delayedarray:<tag>

   (see `bioconductor-delayedarray/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-delayedarray| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-delayedarray.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-delayedarray
   :alt:   (downloads)
.. |docker_bioconductor-delayedarray| image:: https://quay.io/repository/biocontainers/bioconductor-delayedarray/status
   :target: https://quay.io/repository/biocontainers/bioconductor-delayedarray
.. _`bioconductor-delayedarray/tags`: https://quay.io/repository/biocontainers/bioconductor-delayedarray?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-delayedarray/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-delayedarray/README.html
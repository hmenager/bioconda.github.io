:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hdf5array'
.. highlight: bash

bioconductor-hdf5array
======================

.. conda:recipe:: bioconductor-hdf5array
   :replaces_section_title:

   Implements the HDF5Array and TENxMatrix classes\, 2 convenient and memory\-efficient array\-like containers for on\-disk representation of HDF5 datasets. HDF5Array is for datasets that use the conventional \(i.e. dense\) HDF5 representation. TENxMatrix is for datasets that use the HDF5\-based sparse matrix representation from 10x Genomics \(e.g. the 1.3 Million Brain Cell Dataset\). Both containers being DelayedArray extensions\, they support all operations supported by DelayedArray objects. These operations can be either delayed or block\-processed.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/HDF5Array.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-hdf5array <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hdf5array>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hdf5array/meta.yaml>`_
   :links: biotools: :biotools:`hdf5array`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-hdf5array

   |downloads_bioconductor-hdf5array| |docker_bioconductor-hdf5array|

   :versions: 1.12.1-0, 1.10.1-0, 1.8.1-0, 1.6.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-delayedarray: >=0.10.0,<0.11.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rhdf5: >=2.28.0,<2.29.0
   :depends bioconductor-rhdf5lib: >=1.6.0,<1.7.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hdf5array

   and update with::

      conda update bioconductor-hdf5array

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hdf5array:<tag>

   (see `bioconductor-hdf5array/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hdf5array| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hdf5array.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hdf5array
   :alt:   (downloads)
.. |docker_bioconductor-hdf5array| image:: https://quay.io/repository/biocontainers/bioconductor-hdf5array/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hdf5array
.. _`bioconductor-hdf5array/tags`: https://quay.io/repository/biocontainers/bioconductor-hdf5array?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hdf5array/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hdf5array/README.html
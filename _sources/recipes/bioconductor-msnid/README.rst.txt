:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-msnid'
.. highlight: bash

bioconductor-msnid
==================

.. conda:recipe:: bioconductor-msnid
   :replaces_section_title:

   Extracts MS\/MS ID data from mzIdentML \(leveraging mzID package\) or text files. After collating the search results from multiple datasets it assesses their identification quality and optimize filtering criteria to achieve the maximum number of identifications while not exceeding a specified false discovery rate. Also contains a number of utilities to explore the MS\/MS results and assess missed and irregular enzymatic cleavages\, mass measurement accuracy\, etc.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/MSnID.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-msnid <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-msnid>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-msnid/meta.yaml>`_
   :links: biotools: :biotools:`msnid`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-msnid

   |downloads_bioconductor-msnid| |docker_bioconductor-msnid|

   :versions: 1.18.1-0, 1.16.1-0, 1.12.1-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-msnbase: >=2.10.0,<2.11.0
   :depends bioconductor-mzid: >=1.22.0,<1.23.0
   :depends bioconductor-mzr: >=2.18.0,<2.19.0
   :depends bioconductor-protgenerics: >=1.16.0,<1.17.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-doparallel: 
   :depends r-dplyr: 
   :depends r-foreach: 
   :depends r-iterators: 
   :depends r-r.cache: 
   :depends r-rcpp: 
   :depends r-reshape2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-msnid

   and update with::

      conda update bioconductor-msnid

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-msnid:<tag>

   (see `bioconductor-msnid/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-msnid| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-msnid.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-msnid
   :alt:   (downloads)
.. |docker_bioconductor-msnid| image:: https://quay.io/repository/biocontainers/bioconductor-msnid/status
   :target: https://quay.io/repository/biocontainers/bioconductor-msnid
.. _`bioconductor-msnid/tags`: https://quay.io/repository/biocontainers/bioconductor-msnid?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-msnid/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-msnid/README.html
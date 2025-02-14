:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-qcmetrics'
.. highlight: bash

bioconductor-qcmetrics
======================

.. conda:recipe:: bioconductor-qcmetrics
   :replaces_section_title:

   The package provides a framework for generic quality control of data. It permits to create\, manage and visualise individual or sets of quality control metrics and generate quality control reports in various formats.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/qcmetrics.html
   :license: GPL-2
   :recipe: /`bioconductor-qcmetrics <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qcmetrics>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qcmetrics/meta.yaml>`_
   :links: biotools: :biotools:`qcmetrics`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-qcmetrics

   |downloads_bioconductor-qcmetrics| |docker_bioconductor-qcmetrics|

   :versions: 1.22.0-1, 1.20.1-0, 1.20.0-0, 1.18.0-0, 1.16.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-knitr: 
   :depends r-nozzle.r1: 
   :depends r-pander: 
   :depends r-xtable: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-qcmetrics

   and update with::

      conda update bioconductor-qcmetrics

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-qcmetrics:<tag>

   (see `bioconductor-qcmetrics/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-qcmetrics| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-qcmetrics.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-qcmetrics
   :alt:   (downloads)
.. |docker_bioconductor-qcmetrics| image:: https://quay.io/repository/biocontainers/bioconductor-qcmetrics/status
   :target: https://quay.io/repository/biocontainers/bioconductor-qcmetrics
.. _`bioconductor-qcmetrics/tags`: https://quay.io/repository/biocontainers/bioconductor-qcmetrics?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-qcmetrics/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-qcmetrics/README.html
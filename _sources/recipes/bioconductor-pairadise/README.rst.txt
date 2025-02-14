:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pairadise'
.. highlight: bash

bioconductor-pairadise
======================

.. conda:recipe:: bioconductor-pairadise
   :replaces_section_title:

   This package implements the PAIRADISE procedure for detecting differential isoform expression between matched replicates in paired RNA\-Seq data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/PAIRADISE.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-pairadise <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pairadise>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pairadise/meta.yaml>`_

   


.. conda:package:: bioconductor-pairadise

   |downloads_bioconductor-pairadise| |docker_bioconductor-pairadise|

   :versions: 1.0.0-1
   
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-abind: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-nloptr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pairadise

   and update with::

      conda update bioconductor-pairadise

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pairadise:<tag>

   (see `bioconductor-pairadise/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pairadise| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pairadise.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pairadise
   :alt:   (downloads)
.. |docker_bioconductor-pairadise| image:: https://quay.io/repository/biocontainers/bioconductor-pairadise/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pairadise
.. _`bioconductor-pairadise/tags`: https://quay.io/repository/biocontainers/bioconductor-pairadise?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pairadise/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pairadise/README.html
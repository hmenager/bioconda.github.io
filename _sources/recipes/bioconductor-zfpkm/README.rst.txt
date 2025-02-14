:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-zfpkm'
.. highlight: bash

bioconductor-zfpkm
==================

.. conda:recipe:: bioconductor-zfpkm
   :replaces_section_title:

   Perform the zFPKM transform on RNA\-seq FPKM data. This algorithm is based on the publication by Hart et al.\, 2013 \(Pubmed ID 24215113\). Reference recommends using zFPKM \> \-3 to select expressed genes. Validated with encode open\/closed chromosome data. Works well for gene level data using FPKM or TPM. Does not appear to calibrate well for transcript level data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/zFPKM.html
   :license: GPL-3 | file LICENSE
   :recipe: /`bioconductor-zfpkm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-zfpkm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-zfpkm/meta.yaml>`_

   


.. conda:package:: bioconductor-zfpkm

   |downloads_bioconductor-zfpkm| |docker_bioconductor-zfpkm|

   :versions: 1.6.0-1, 1.4.0-0, 1.2.0-0, 1.0.0-0
   
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-checkmate: 
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-zfpkm

   and update with::

      conda update bioconductor-zfpkm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-zfpkm:<tag>

   (see `bioconductor-zfpkm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-zfpkm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-zfpkm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-zfpkm
   :alt:   (downloads)
.. |docker_bioconductor-zfpkm| image:: https://quay.io/repository/biocontainers/bioconductor-zfpkm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-zfpkm
.. _`bioconductor-zfpkm/tags`: https://quay.io/repository/biocontainers/bioconductor-zfpkm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-zfpkm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-zfpkm/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mitoodedata'
.. highlight: bash

bioconductor-mitoodedata
========================

.. conda:recipe:: bioconductor-mitoodedata
   :replaces_section_title:

   This package contains the experimental data \(assay annotation\, siRNA annotation\, time\-lapse cell counts\) associated to the paper \"Dynamical modelling of phenotypes in a genome\-wide RNAi live\-cell imaging assay\" \(submitted\). The data ultimately come from the Mitocheck assay reported in \"Phenotypic profiling of the human genome by time\-lapse microscopy reveals cell division genes\" \(Neumann\, Walter et al\, Nature 2010\).

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/mitoODEdata.html
   :license: LGPL
   :recipe: /`bioconductor-mitoodedata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mitoodedata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mitoodedata/meta.yaml>`_

   


.. conda:package:: bioconductor-mitoodedata

   |downloads_bioconductor-mitoodedata| |docker_bioconductor-mitoodedata|

   :versions: 1.20.0-1, 1.20.0-0, 1.18.0-0
   
   :depends curl: >=7.64.1,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mitoodedata

   and update with::

      conda update bioconductor-mitoodedata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mitoodedata:<tag>

   (see `bioconductor-mitoodedata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mitoodedata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mitoodedata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mitoodedata
   :alt:   (downloads)
.. |docker_bioconductor-mitoodedata| image:: https://quay.io/repository/biocontainers/bioconductor-mitoodedata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mitoodedata
.. _`bioconductor-mitoodedata/tags`: https://quay.io/repository/biocontainers/bioconductor-mitoodedata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mitoodedata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mitoodedata/README.html
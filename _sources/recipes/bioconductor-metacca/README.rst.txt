:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-metacca'
.. highlight: bash

bioconductor-metacca
====================

.. conda:recipe:: bioconductor-metacca
   :replaces_section_title:

   metaCCA performs multivariate analysis of a single or multiple GWAS based on univariate regression coefficients. It allows multivariate representation of both phenotype and genotype. metaCCA extends the statistical technique of canonical correlation analysis to the setting where original individual\-level records are not available\, and employs a covariance shrinkage algorithm to achieve robustness.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/metaCCA.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-metacca <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-metacca>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-metacca/meta.yaml>`_
   :links: biotools: :biotools:`metacca`

   


.. conda:package:: bioconductor-metacca

   |downloads_bioconductor-metacca| |docker_bioconductor-metacca|

   :versions: 1.12.0-1, 1.12.0-0, 1.10.0-0, 1.8.0-0, 1.6.0-0, 1.4.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-metacca

   and update with::

      conda update bioconductor-metacca

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-metacca:<tag>

   (see `bioconductor-metacca/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-metacca| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-metacca.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-metacca
   :alt:   (downloads)
.. |docker_bioconductor-metacca| image:: https://quay.io/repository/biocontainers/bioconductor-metacca/status
   :target: https://quay.io/repository/biocontainers/bioconductor-metacca
.. _`bioconductor-metacca/tags`: https://quay.io/repository/biocontainers/bioconductor-metacca?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-metacca/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-metacca/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ecoliasv2cdf'
.. highlight: bash

bioconductor-ecoliasv2cdf
=========================

.. conda:recipe:: bioconductor-ecoliasv2cdf
   :replaces_section_title:

   A package containing an environment representing the Ecoli\_ASv2.CDF file.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/ecoliasv2cdf.html
   :license: LGPL
   :recipe: /`bioconductor-ecoliasv2cdf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ecoliasv2cdf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ecoliasv2cdf/meta.yaml>`_

   


.. conda:package:: bioconductor-ecoliasv2cdf

   |downloads_bioconductor-ecoliasv2cdf| |docker_bioconductor-ecoliasv2cdf|

   :versions: 2.18.0-2, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ecoliasv2cdf

   and update with::

      conda update bioconductor-ecoliasv2cdf

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ecoliasv2cdf:<tag>

   (see `bioconductor-ecoliasv2cdf/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ecoliasv2cdf| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ecoliasv2cdf.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ecoliasv2cdf
   :alt:   (downloads)
.. |docker_bioconductor-ecoliasv2cdf| image:: https://quay.io/repository/biocontainers/bioconductor-ecoliasv2cdf/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ecoliasv2cdf
.. _`bioconductor-ecoliasv2cdf/tags`: https://quay.io/repository/biocontainers/bioconductor-ecoliasv2cdf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ecoliasv2cdf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ecoliasv2cdf/README.html
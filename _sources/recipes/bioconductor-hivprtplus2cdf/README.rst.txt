:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hivprtplus2cdf'
.. highlight: bash

bioconductor-hivprtplus2cdf
===========================

.. conda:recipe:: bioconductor-hivprtplus2cdf
   :replaces_section_title:

   A package containing an environment representing the HIV PRTPlus 2.CDF file.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/hivprtplus2cdf.html
   :license: LGPL
   :recipe: /`bioconductor-hivprtplus2cdf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hivprtplus2cdf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hivprtplus2cdf/meta.yaml>`_

   


.. conda:package:: bioconductor-hivprtplus2cdf

   |downloads_bioconductor-hivprtplus2cdf| |docker_bioconductor-hivprtplus2cdf|

   :versions: 2.18.0-2, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hivprtplus2cdf

   and update with::

      conda update bioconductor-hivprtplus2cdf

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hivprtplus2cdf:<tag>

   (see `bioconductor-hivprtplus2cdf/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hivprtplus2cdf| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hivprtplus2cdf.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hivprtplus2cdf
   :alt:   (downloads)
.. |docker_bioconductor-hivprtplus2cdf| image:: https://quay.io/repository/biocontainers/bioconductor-hivprtplus2cdf/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hivprtplus2cdf
.. _`bioconductor-hivprtplus2cdf/tags`: https://quay.io/repository/biocontainers/bioconductor-hivprtplus2cdf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hivprtplus2cdf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hivprtplus2cdf/README.html
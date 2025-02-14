:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-primeviewcdf'
.. highlight: bash

bioconductor-primeviewcdf
=========================

.. conda:recipe:: bioconductor-primeviewcdf
   :replaces_section_title:

   A package containing an environment representing the PrimeView.cdf file.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/primeviewcdf.html
   :license: LGPL
   :recipe: /`bioconductor-primeviewcdf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-primeviewcdf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-primeviewcdf/meta.yaml>`_

   


.. conda:package:: bioconductor-primeviewcdf

   |downloads_bioconductor-primeviewcdf| |docker_bioconductor-primeviewcdf|

   :versions: 2.18.0-2, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-primeviewcdf

   and update with::

      conda update bioconductor-primeviewcdf

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-primeviewcdf:<tag>

   (see `bioconductor-primeviewcdf/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-primeviewcdf| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-primeviewcdf.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-primeviewcdf
   :alt:   (downloads)
.. |docker_bioconductor-primeviewcdf| image:: https://quay.io/repository/biocontainers/bioconductor-primeviewcdf/status
   :target: https://quay.io/repository/biocontainers/bioconductor-primeviewcdf
.. _`bioconductor-primeviewcdf/tags`: https://quay.io/repository/biocontainers/bioconductor-primeviewcdf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-primeviewcdf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-primeviewcdf/README.html
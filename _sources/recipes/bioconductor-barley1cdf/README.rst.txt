:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-barley1cdf'
.. highlight: bash

bioconductor-barley1cdf
=======================

.. conda:recipe:: bioconductor-barley1cdf
   :replaces_section_title:

   A package containing an environment representing the Barley1.CDF file.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/barley1cdf.html
   :license: LGPL
   :recipe: /`bioconductor-barley1cdf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-barley1cdf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-barley1cdf/meta.yaml>`_

   


.. conda:package:: bioconductor-barley1cdf

   |downloads_bioconductor-barley1cdf| |docker_bioconductor-barley1cdf|

   :versions: 2.18.0-2, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-barley1cdf

   and update with::

      conda update bioconductor-barley1cdf

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-barley1cdf:<tag>

   (see `bioconductor-barley1cdf/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-barley1cdf| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-barley1cdf.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-barley1cdf
   :alt:   (downloads)
.. |docker_bioconductor-barley1cdf| image:: https://quay.io/repository/biocontainers/bioconductor-barley1cdf/status
   :target: https://quay.io/repository/biocontainers/bioconductor-barley1cdf
.. _`bioconductor-barley1cdf/tags`: https://quay.io/repository/biocontainers/bioconductor-barley1cdf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-barley1cdf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-barley1cdf/README.html
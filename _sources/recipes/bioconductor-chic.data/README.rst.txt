:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chic.data'
.. highlight: bash

bioconductor-chic.data
======================

.. conda:recipe:: bioconductor-chic.data
   :replaces_section_title:

   This package contains annotation and metagene profile data for the ChIC package.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/ChIC.data.html
   :license: GPL-2
   :recipe: /`bioconductor-chic.data <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chic.data>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chic.data/meta.yaml>`_

   


.. conda:package:: bioconductor-chic.data

   |downloads_bioconductor-chic.data| |docker_bioconductor-chic.data|

   :versions: 1.4.0-1, 1.4.0-0, 1.2.0-0
   
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-caret: >=6.0-78
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chic.data

   and update with::

      conda update bioconductor-chic.data

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chic.data:<tag>

   (see `bioconductor-chic.data/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chic.data| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chic.data.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chic.data
   :alt:   (downloads)
.. |docker_bioconductor-chic.data| image:: https://quay.io/repository/biocontainers/bioconductor-chic.data/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chic.data
.. _`bioconductor-chic.data/tags`: https://quay.io/repository/biocontainers/bioconductor-chic.data?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chic.data/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chic.data/README.html
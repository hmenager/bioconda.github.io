:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-spem'
.. highlight: bash

bioconductor-spem
=================

.. conda:recipe:: bioconductor-spem
   :replaces_section_title:

   This package can optimize the parameter in S\-system models given time series data

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/SPEM.html
   :license: GPL-2
   :recipe: /`bioconductor-spem <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spem>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spem/meta.yaml>`_
   :links: biotools: :biotools:`spem`, doi: :doi:`10.1089/cmb.2011.0269`

   


.. conda:package:: bioconductor-spem

   |downloads_bioconductor-spem| |docker_bioconductor-spem|

   :versions: 1.24.0-1, 1.22.0-0, 1.20.0-0, 1.18.0-0, 1.16.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-rsolnp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-spem

   and update with::

      conda update bioconductor-spem

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-spem:<tag>

   (see `bioconductor-spem/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-spem| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-spem.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-spem
   :alt:   (downloads)
.. |docker_bioconductor-spem| image:: https://quay.io/repository/biocontainers/bioconductor-spem/status
   :target: https://quay.io/repository/biocontainers/bioconductor-spem
.. _`bioconductor-spem/tags`: https://quay.io/repository/biocontainers/bioconductor-spem?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-spem/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-spem/README.html
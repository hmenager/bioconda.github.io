:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-spacepac'
.. highlight: bash

bioconductor-spacepac
=====================

.. conda:recipe:: bioconductor-spacepac
   :replaces_section_title:

   Identifies clustering of somatic mutations in proteins via a simulation approach while considering the protein\'s tertiary structure.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/SpacePAC.html
   :license: GPL-2
   :recipe: /`bioconductor-spacepac <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spacepac>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spacepac/meta.yaml>`_
   :links: biotools: :biotools:`spacepac`, doi: :doi:`10.1186/1471-2105-15-231`

   


.. conda:package:: bioconductor-spacepac

   |downloads_bioconductor-spacepac| |docker_bioconductor-spacepac|

   :versions: 1.22.0-1, 1.20.0-0, 1.18.3-0, 1.16.0-0
   
   :depends bioconductor-ipac: >=1.28.0,<1.29.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-spacepac

   and update with::

      conda update bioconductor-spacepac

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-spacepac:<tag>

   (see `bioconductor-spacepac/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-spacepac| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-spacepac.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-spacepac
   :alt:   (downloads)
.. |docker_bioconductor-spacepac| image:: https://quay.io/repository/biocontainers/bioconductor-spacepac/status
   :target: https://quay.io/repository/biocontainers/bioconductor-spacepac
.. _`bioconductor-spacepac/tags`: https://quay.io/repository/biocontainers/bioconductor-spacepac?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-spacepac/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-spacepac/README.html
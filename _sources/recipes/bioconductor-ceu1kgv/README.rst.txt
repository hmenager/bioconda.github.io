:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ceu1kgv'
.. highlight: bash

bioconductor-ceu1kgv
====================

.. conda:recipe:: bioconductor-ceu1kgv
   :replaces_section_title:

   expression \+ genotype on 79 unrelated CEU individuals

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/ceu1kgv.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ceu1kgv <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ceu1kgv>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ceu1kgv/meta.yaml>`_

   


.. conda:package:: bioconductor-ceu1kgv

   |downloads_bioconductor-ceu1kgv| |docker_bioconductor-ceu1kgv|

   :versions: 0.26.0-1, 0.24.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-ggbase: >=3.46.0,<3.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ceu1kgv

   and update with::

      conda update bioconductor-ceu1kgv

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ceu1kgv:<tag>

   (see `bioconductor-ceu1kgv/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ceu1kgv| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ceu1kgv.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ceu1kgv
   :alt:   (downloads)
.. |docker_bioconductor-ceu1kgv| image:: https://quay.io/repository/biocontainers/bioconductor-ceu1kgv/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ceu1kgv
.. _`bioconductor-ceu1kgv/tags`: https://quay.io/repository/biocontainers/bioconductor-ceu1kgv?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ceu1kgv/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ceu1kgv/README.html
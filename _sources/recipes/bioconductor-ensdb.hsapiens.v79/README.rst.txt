:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ensdb.hsapiens.v79'
.. highlight: bash

bioconductor-ensdb.hsapiens.v79
===============================

.. conda:recipe:: bioconductor-ensdb.hsapiens.v79
   :replaces_section_title:

   Exposes an annotation databases generated from Ensembl.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/EnsDb.Hsapiens.v79.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ensdb.hsapiens.v79 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ensdb.hsapiens.v79>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ensdb.hsapiens.v79/meta.yaml>`_

   


.. conda:package:: bioconductor-ensdb.hsapiens.v79

   |downloads_bioconductor-ensdb.hsapiens.v79| |docker_bioconductor-ensdb.hsapiens.v79|

   :versions: 2.99.0-2, 2.99.0-0
   
   :depends bioconductor-ensembldb: >=2.8.0,<2.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ensdb.hsapiens.v79

   and update with::

      conda update bioconductor-ensdb.hsapiens.v79

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ensdb.hsapiens.v79:<tag>

   (see `bioconductor-ensdb.hsapiens.v79/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ensdb.hsapiens.v79| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ensdb.hsapiens.v79.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ensdb.hsapiens.v79
   :alt:   (downloads)
.. |docker_bioconductor-ensdb.hsapiens.v79| image:: https://quay.io/repository/biocontainers/bioconductor-ensdb.hsapiens.v79/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ensdb.hsapiens.v79
.. _`bioconductor-ensdb.hsapiens.v79/tags`: https://quay.io/repository/biocontainers/bioconductor-ensdb.hsapiens.v79?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ensdb.hsapiens.v79/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ensdb.hsapiens.v79/README.html
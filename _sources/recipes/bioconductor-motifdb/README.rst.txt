:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-motifdb'
.. highlight: bash

bioconductor-motifdb
====================

.. conda:recipe:: bioconductor-motifdb
   :replaces_section_title:

   More than 9900 annotated position frequency matrices from 14 public sources\, for multiple organisms.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/MotifDb.html
   :license: Artistic-2.0 | file LICENSE
   :recipe: /`bioconductor-motifdb <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-motifdb>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-motifdb/meta.yaml>`_
   :links: biotools: :biotools:`motifdb`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-motifdb

   |downloads_bioconductor-motifdb| |docker_bioconductor-motifdb|

   :versions: 1.26.0-1, 1.24.1-0, 1.22.0-0, 1.20.0-0, 1.18.0-0, 1.16.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-splitstackshape: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-motifdb

   and update with::

      conda update bioconductor-motifdb

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-motifdb:<tag>

   (see `bioconductor-motifdb/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-motifdb| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-motifdb.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-motifdb
   :alt:   (downloads)
.. |docker_bioconductor-motifdb| image:: https://quay.io/repository/biocontainers/bioconductor-motifdb/status
   :target: https://quay.io/repository/biocontainers/bioconductor-motifdb
.. _`bioconductor-motifdb/tags`: https://quay.io/repository/biocontainers/bioconductor-motifdb?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-motifdb/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-motifdb/README.html
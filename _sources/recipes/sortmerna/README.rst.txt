:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'sortmerna'
.. highlight: bash

sortmerna
=========

.. conda:recipe:: sortmerna/2.1b
   :replaces_section_title:

   SortMeRNA is a biological sequence analysis tool for filtering\, mapping and OTU\-picking NGS reads.

   :homepage: http://bioinfo.lifl.fr/RNA/sortmerna
   :license: LGPL
   :recipe: /`sortmerna <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sortmerna>`_/`2.1b <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sortmerna/2.1b>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sortmerna/2.1b/meta.yaml>`_
   :links: biotools: :biotools:`sortmerna`, doi: :doi:`10.1093/bioinformatics/bts611`

   


.. conda:package:: sortmerna

   |downloads_sortmerna| |docker_sortmerna|

   :versions: 2.1b-4, 2.1b-3, 2.1b-2, 2.1b-1, 2.1b-0, 2.0-4, 2.0-3, 2.0-2, 2.0-1, 2.0-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install sortmerna

   and update with::

      conda update sortmerna

   or use the docker container::

      docker pull quay.io/biocontainers/sortmerna:<tag>

   (see `sortmerna/tags`_ for valid values for ``<tag>``)


.. |downloads_sortmerna| image:: https://img.shields.io/conda/dn/bioconda/sortmerna.svg?style=flat
   :target: https://anaconda.org/bioconda/sortmerna
   :alt:   (downloads)
.. |docker_sortmerna| image:: https://quay.io/repository/biocontainers/sortmerna/status
   :target: https://quay.io/repository/biocontainers/sortmerna
.. _`sortmerna/tags`: https://quay.io/repository/biocontainers/sortmerna?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/sortmerna/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/sortmerna/README.html
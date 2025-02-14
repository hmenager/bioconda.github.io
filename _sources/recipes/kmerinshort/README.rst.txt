:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'kmerinshort'
.. highlight: bash

kmerinshort
===========

.. conda:recipe:: kmerinshort
   :replaces_section_title:

   KmerInShort counts kmers from a fasta\/fastq file or list of files\, and outputs results in a text file. It is limited to short kmers \(k\<15\). It is a part of the FEELnc pipeline \(V.Wucher et al.\)

   :homepage: https://github.com/rizkg/KmerInShort
   :license: aGPL v3
   :recipe: /`kmerinshort <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/kmerinshort>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/kmerinshort/meta.yaml>`_

   


.. conda:package:: kmerinshort

   |downloads_kmerinshort| |docker_kmerinshort|

   :versions: 1.0.1-1, 1.0.1-0
   
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install kmerinshort

   and update with::

      conda update kmerinshort

   or use the docker container::

      docker pull quay.io/biocontainers/kmerinshort:<tag>

   (see `kmerinshort/tags`_ for valid values for ``<tag>``)


.. |downloads_kmerinshort| image:: https://img.shields.io/conda/dn/bioconda/kmerinshort.svg?style=flat
   :target: https://anaconda.org/bioconda/kmerinshort
   :alt:   (downloads)
.. |docker_kmerinshort| image:: https://quay.io/repository/biocontainers/kmerinshort/status
   :target: https://quay.io/repository/biocontainers/kmerinshort
.. _`kmerinshort/tags`: https://quay.io/repository/biocontainers/kmerinshort?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/kmerinshort/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/kmerinshort/README.html
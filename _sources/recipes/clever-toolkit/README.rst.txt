:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'clever-toolkit'
.. highlight: bash

clever-toolkit
==============

.. conda:recipe:: clever-toolkit
   :replaces_section_title:

   The clever toolkit \(CTK\) is a suite of tools to analyze next\-generation sequencing data and\, in particular\, to discover and genotype insertions and deletions from paired\-end reads.

   :homepage: https://bitbucket.org/tobiasmarschall/clever-toolkit
   :license: GPLv3
   :recipe: /`clever-toolkit <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/clever-toolkit>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/clever-toolkit/meta.yaml>`_

   


.. conda:package:: clever-toolkit

   |downloads_clever-toolkit| |docker_clever-toolkit|

   :versions: 2.4-6, 2.4-5, 2.4-0, 2.3-0, 2.2.1-0, 2.1-3, 2.0rc4-3, 2.0rc4-2, 2.0rc3-1, 2.0rc3-0
   
   :depends bcftools: >=1
   :depends bedtools: >=2.26
   :depends boost: >=1.68.0,<1.68.1.0a0
   :depends bwa: 
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends make: 
   :depends matplotlib: 2.*
   :depends python: >=3.6,<3.7.0a0
   :depends samtools: >=1
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install clever-toolkit

   and update with::

      conda update clever-toolkit

   or use the docker container::

      docker pull quay.io/biocontainers/clever-toolkit:<tag>

   (see `clever-toolkit/tags`_ for valid values for ``<tag>``)


.. |downloads_clever-toolkit| image:: https://img.shields.io/conda/dn/bioconda/clever-toolkit.svg?style=flat
   :target: https://anaconda.org/bioconda/clever-toolkit
   :alt:   (downloads)
.. |docker_clever-toolkit| image:: https://quay.io/repository/biocontainers/clever-toolkit/status
   :target: https://quay.io/repository/biocontainers/clever-toolkit
.. _`clever-toolkit/tags`: https://quay.io/repository/biocontainers/clever-toolkit?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/clever-toolkit/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/clever-toolkit/README.html
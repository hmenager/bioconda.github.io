:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'snippy'
.. highlight: bash

snippy
======

.. conda:recipe:: snippy
   :replaces_section_title:

   Rapid bacterial SNP calling and core genome alignments

   :homepage: https://github.com/tseemann/snippy
   :license: GPL / GPL-2.0
   :recipe: /`snippy <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/snippy>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/snippy/meta.yaml>`_
   :links: biotools: :biotools:`snippy`

   


.. conda:package:: snippy

   |downloads_snippy| |docker_snippy|

   :versions: 4.4.3-1, 4.4.3-0, 4.4.1-0, 4.4.0-2, 4.4.0-1, 4.4.0-0, 4.3.6-0, 4.3.5-0, 4.3.3-0, 4.2.3-0, 4.1.0-0, 4.0.7-0, 4.0.5-0, 4.0.2-0, 3.2-1, 3.1-4, 3.1-3, 3.1-2, 3.1-1, 3.1-0, 3.0-1, 3.0-0, 2.9-1, 2.9-0
   
   :depends bcftools: >=1.9
   :depends bedtools: >=2.28.0
   :depends bwa: >=0.7.17
   :depends emboss: >=6.0
   :depends freebayes: >=1.3.1
   :depends minimap2: >=2.10
   :depends openjdk: 8.*
   :depends parallel: >=20170422
   :depends perl: >=5.26
   :depends perl-bioperl: >=1.7.2
   :depends perl-time-piece: 
   :depends samclip: >=0.2
   :depends samtools: >=1.9
   :depends seqtk: >=1.2
   :depends snp-sites: >=2.4
   :depends snpeff: >=4.3
   :depends vcflib: >=1.0.0_rc3
   :depends vt: >=0.5772
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install snippy

   and update with::

      conda update snippy

   or use the docker container::

      docker pull quay.io/biocontainers/snippy:<tag>

   (see `snippy/tags`_ for valid values for ``<tag>``)


.. |downloads_snippy| image:: https://img.shields.io/conda/dn/bioconda/snippy.svg?style=flat
   :target: https://anaconda.org/bioconda/snippy
   :alt:   (downloads)
.. |docker_snippy| image:: https://quay.io/repository/biocontainers/snippy/status
   :target: https://quay.io/repository/biocontainers/snippy
.. _`snippy/tags`: https://quay.io/repository/biocontainers/snippy?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/snippy/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/snippy/README.html
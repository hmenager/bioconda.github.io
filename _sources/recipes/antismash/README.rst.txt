:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'antismash'
.. highlight: bash

antismash
=========

.. conda:recipe:: antismash
   :replaces_section_title:

   antiSMASH allows the rapid genome\-wide identification\, annotation and analysis of secondary metabolite biosynthesis gene clusters.

   :homepage: http://antismash.secondarymetabolites.org/
   :license: AGPL / AGPL-3.0
   :recipe: /`antismash <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/antismash>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/antismash/meta.yaml>`_
   :links: biotools: :biotools:`antismash`

   


.. conda:package:: antismash

   |downloads_antismash| |docker_antismash|

   :versions: 4.2.0-1, 4.1.0-1, 4.1.0-0, 4.0.2-3, 4.0.2-2, 4.0.2-1, 4.0.1-1
   
   :depends argparse: 
   :depends backports.lzma: 
   :depends bcbio-gff: 
   :depends biopython: >=1.65
   :depends blast: 2.2.*
   :depends clustalw: 
   :depends cssselect: 
   :depends diamond: 0.8.*
   :depends ete2: 
   :depends fasttree: 2.1.*
   :depends glimmer: 3.02
   :depends glimmerhmm: 3.0.*
   :depends helperlibs: 
   :depends hmmer: 3.1b2
   :depends hmmer2: 
   :depends icu: >=58.2,<59.0a0
   :depends libxml2: 2.9.*
   :depends mafft: 
   :depends matplotlib: 
   :depends meme: 4.11.2
   :depends muscle: 
   :depends networkx: 
   :depends numpy: 
   :depends openjdk: 
   :depends pandas: 
   :depends perl: 5.26.*
   :depends perl-bioperl: 
   :depends prodigal: 
   :depends pyexcelerator: 
   :depends pyquery: 1.2.*
   :depends pysvg: 
   :depends python: >=2.7,<2.8.0a0
   :depends scikit-learn: 0.18.*
   :depends scipy: 
   :depends xz: 5.2.*
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install antismash

   and update with::

      conda update antismash

   or use the docker container::

      docker pull quay.io/biocontainers/antismash:<tag>

   (see `antismash/tags`_ for valid values for ``<tag>``)


.. |downloads_antismash| image:: https://img.shields.io/conda/dn/bioconda/antismash.svg?style=flat
   :target: https://anaconda.org/bioconda/antismash
   :alt:   (downloads)
.. |docker_antismash| image:: https://quay.io/repository/biocontainers/antismash/status
   :target: https://quay.io/repository/biocontainers/antismash
.. _`antismash/tags`: https://quay.io/repository/biocontainers/antismash?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/antismash/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/antismash/README.html
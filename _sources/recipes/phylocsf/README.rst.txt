:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'phylocsf'
.. highlight: bash

phylocsf
========

.. conda:recipe:: phylocsf
   :replaces_section_title:

   Phylogenetic analysis of multi\-species genome sequence alignments to identify conserved protein\-coding regions

   :homepage: https://github.com/mlin/PhyloCSF/wiki
   :license: AGPL-3.0
   :recipe: /`phylocsf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/phylocsf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/phylocsf/meta.yaml>`_
   :links: biotools: :biotools:`phyloCSF`

   


.. conda:package:: phylocsf

   |downloads_phylocsf| |docker_phylocsf|

   :versions: 1.0.1-0
   
   :depends gsl: 
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends ocaml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install phylocsf

   and update with::

      conda update phylocsf

   or use the docker container::

      docker pull quay.io/biocontainers/phylocsf:<tag>

   (see `phylocsf/tags`_ for valid values for ``<tag>``)


.. |downloads_phylocsf| image:: https://img.shields.io/conda/dn/bioconda/phylocsf.svg?style=flat
   :target: https://anaconda.org/bioconda/phylocsf
   :alt:   (downloads)
.. |docker_phylocsf| image:: https://quay.io/repository/biocontainers/phylocsf/status
   :target: https://quay.io/repository/biocontainers/phylocsf
.. _`phylocsf/tags`: https://quay.io/repository/biocontainers/phylocsf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/phylocsf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/phylocsf/README.html
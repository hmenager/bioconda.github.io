:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'pash'
.. highlight: bash

pash
====

.. conda:recipe:: pash
   :replaces_section_title:

   A versatile software package for read mapping and integrative analysis of genomic and epigenomic variation using massively parallel DNA sequencing

   :homepage: http://www.bioinformatics.bbsrc.ac.uk/projects/bismark/
   :license: Unknown
   :recipe: /`pash <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pash>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pash/meta.yaml>`_
   :links: biotools: :biotools:`pash`

   


.. conda:package:: pash

   |downloads_pash| |docker_pash|

   :versions: 3.0.6.2-0
   
   :depends glib: 
   :depends libgcc: 
   :depends ruby: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install pash

   and update with::

      conda update pash

   or use the docker container::

      docker pull quay.io/biocontainers/pash:<tag>

   (see `pash/tags`_ for valid values for ``<tag>``)


.. |downloads_pash| image:: https://img.shields.io/conda/dn/bioconda/pash.svg?style=flat
   :target: https://anaconda.org/bioconda/pash
   :alt:   (downloads)
.. |docker_pash| image:: https://quay.io/repository/biocontainers/pash/status
   :target: https://quay.io/repository/biocontainers/pash
.. _`pash/tags`: https://quay.io/repository/biocontainers/pash?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/pash/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/pash/README.html
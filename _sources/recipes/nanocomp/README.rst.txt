:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'nanocomp'
.. highlight: bash

nanocomp
========

.. conda:recipe:: nanocomp
   :replaces_section_title:

   Comparing runs of Oxford Nanopore sequencing data and alignments

   :homepage: https://github.com/wdecoster/NanoComp
   :license: MIT / MIT License
   :recipe: /`nanocomp <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/nanocomp>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/nanocomp/meta.yaml>`_

   


.. conda:package:: nanocomp

   |downloads_nanocomp| |docker_nanocomp|

   :versions: 1.9.2-0, 1.9.1-0, 1.9.0-0, 1.8.0-0, 1.7.0-0, 1.6.0-0, 1.1.0-1, 1.1.0-0, 1.0.0-0, 0.23.1-0, 0.23.0-1, 0.19.0-1, 0.19.0-0, 0.16.0-0, 0.15.0-0, 0.12.4-0, 0.7.0-0, 0.5.0-0
   
   :depends nanoget: >=1.4.0
   :depends nanomath: >=0.15.3
   :depends nanoplot: >=1.17.3
   :depends nanoplotter: >=1.0.0
   :depends numpy: 
   :depends orca: 
   :depends pandas: 
   :depends pysam: >=0.15
   :depends python: >=3
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install nanocomp

   and update with::

      conda update nanocomp

   or use the docker container::

      docker pull quay.io/biocontainers/nanocomp:<tag>

   (see `nanocomp/tags`_ for valid values for ``<tag>``)


.. |downloads_nanocomp| image:: https://img.shields.io/conda/dn/bioconda/nanocomp.svg?style=flat
   :target: https://anaconda.org/bioconda/nanocomp
   :alt:   (downloads)
.. |docker_nanocomp| image:: https://quay.io/repository/biocontainers/nanocomp/status
   :target: https://quay.io/repository/biocontainers/nanocomp
.. _`nanocomp/tags`: https://quay.io/repository/biocontainers/nanocomp?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/nanocomp/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/nanocomp/README.html
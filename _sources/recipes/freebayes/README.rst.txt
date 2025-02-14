:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'freebayes'
.. highlight: bash

freebayes
=========

.. conda:recipe:: freebayes
   :replaces_section_title:

   Bayesian haplotype\-based polymorphism discovery and genotyping

   :homepage: https://github.com/ekg/freebayes
   :license: MIT / MIT
   :recipe: /`freebayes <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/freebayes>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/freebayes/meta.yaml>`_
   :links: biotools: :biotools:`freebayes`

   


.. conda:package:: freebayes

   |downloads_freebayes| |docker_freebayes|

   :versions: 1.3.1-0, 1.2.0-4, 1.2.0-3, 1.2.0-2, 1.2.0-0, 1.1.0.46-5, 1.1.0.46-4, 1.1.0.46-3, 1.1.0.46-2, 1.1.0.46-1, 1.1.0.46-0, 1.1.0-3, 1.1.0-2, 1.1.0-1, 1.1.0-0, 1.0.2.29-2, 1.0.2.29-1, 1.0.2.29-0, 1.0.2-0, 1.0.1-0, 0.9.21.26-0, 0.9.21.7-0
   
   :depends bzip2: >=1.0.6,<2.0a0
   :depends htslib: 
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends parallel: 
   :depends python: >=2.7,<2.8.0a0
   :depends xz: >=5.2.4,<5.3.0a0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install freebayes

   and update with::

      conda update freebayes

   or use the docker container::

      docker pull quay.io/biocontainers/freebayes:<tag>

   (see `freebayes/tags`_ for valid values for ``<tag>``)


.. |downloads_freebayes| image:: https://img.shields.io/conda/dn/bioconda/freebayes.svg?style=flat
   :target: https://anaconda.org/bioconda/freebayes
   :alt:   (downloads)
.. |docker_freebayes| image:: https://quay.io/repository/biocontainers/freebayes/status
   :target: https://quay.io/repository/biocontainers/freebayes
.. _`freebayes/tags`: https://quay.io/repository/biocontainers/freebayes?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/freebayes/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/freebayes/README.html
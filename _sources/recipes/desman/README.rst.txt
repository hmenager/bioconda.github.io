:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'desman'
.. highlight: bash

desman
======

.. conda:recipe:: desman
   :replaces_section_title:

   De novo Extraction of Strains from MetAgeNomes

   :homepage: https://github.com/chrisquince/DESMAN
   :license: BSD / BSD
   :recipe: /`desman <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/desman>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/desman/meta.yaml>`_
   :links: doi: :doi:`10.1186/s13059-017-1309-9`

   


.. conda:package:: desman

   |downloads_desman| |docker_desman|

   :versions: 2.1-2, 2.1-1, 2.1-0
   
   :depends bcbio-gff: 
   :depends biopython: 
   :depends cython: >=0.19.1
   :depends gsl: >=2.4,<2.5.0a0
   :depends libgcc-ng: >=7.3.0
   :depends numpy: >=1.7.1
   :depends pandas: >=0.11.0
   :depends pysam: 
   :depends python: >=3.6,<3.7.0a0
   :depends r-getopt: 
   :depends r-ggplot2: >=2.2.2
   :depends r-labeling: 
   :depends r-reshape: >=0.8.7
   :depends scikit-learn: 
   :depends scipy: >=0.12.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install desman

   and update with::

      conda update desman

   or use the docker container::

      docker pull quay.io/biocontainers/desman:<tag>

   (see `desman/tags`_ for valid values for ``<tag>``)


.. |downloads_desman| image:: https://img.shields.io/conda/dn/bioconda/desman.svg?style=flat
   :target: https://anaconda.org/bioconda/desman
   :alt:   (downloads)
.. |docker_desman| image:: https://quay.io/repository/biocontainers/desman/status
   :target: https://quay.io/repository/biocontainers/desman
.. _`desman/tags`: https://quay.io/repository/biocontainers/desman?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/desman/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/desman/README.html
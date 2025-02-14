:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'metaseq'
.. highlight: bash

metaseq
=======

.. conda:recipe:: metaseq
   :replaces_section_title:

   Framework for integrated analysis and plotting of ChIP\/RIP\/RNA\/\*\-seq data.

   :homepage: http://github.com/daler/metaseq
   :license: MIT / MIT
   :recipe: /`metaseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/metaseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/metaseq/meta.yaml>`_

   


.. conda:package:: metaseq

   |downloads_metaseq| |docker_metaseq|

   :versions: 0.5.6-2, 0.5.6-0
   
   :depends biopython: 
   :depends bx-python: >=0.7.1
   :depends cython: 
   :depends fisher: 
   :depends gffutils: >=0.8.2
   :depends matplotlib: >=1.3.1
   :depends numpy: >=1.8.0
   :depends pandas: >=0.13.1
   :depends pybedtools: >=0.6.6
   :depends pysam: >=0.7
   :depends python: >=2.7,<2.8.0a0
   :depends pyyaml: >=3.10
   :depends scikit-learn: 
   :depends scipy: >=0.10.1
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install metaseq

   and update with::

      conda update metaseq

   or use the docker container::

      docker pull quay.io/biocontainers/metaseq:<tag>

   (see `metaseq/tags`_ for valid values for ``<tag>``)


.. |downloads_metaseq| image:: https://img.shields.io/conda/dn/bioconda/metaseq.svg?style=flat
   :target: https://anaconda.org/bioconda/metaseq
   :alt:   (downloads)
.. |docker_metaseq| image:: https://quay.io/repository/biocontainers/metaseq/status
   :target: https://quay.io/repository/biocontainers/metaseq
.. _`metaseq/tags`: https://quay.io/repository/biocontainers/metaseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/metaseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/metaseq/README.html
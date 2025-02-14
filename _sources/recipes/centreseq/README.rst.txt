:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'centreseq'
.. highlight: bash

centreseq
=========

.. conda:recipe:: centreseq
   :replaces_section_title:

   Fast generation of a core genome among bacterial strains

   :homepage: https://github.com/bfssi-forest-dussault/centreseq
   :license: MIT / MIT
   :recipe: /`centreseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/centreseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/centreseq/meta.yaml>`_

   


.. conda:package:: centreseq

   |downloads_centreseq| |docker_centreseq|

   :versions: 0.3.0-0, v0.2.3-0
   
   :depends biopython: >=1.70
   :depends click: >=7.0
   :depends cyvcf2: 
   :depends dataclasses: >=0.6
   :depends minced: 
   :depends mmseqs2: 
   :depends muscle: 
   :depends pandas: >=0.24.0
   :depends prokka: 
   :depends python: >=3.6
   :depends scipy: >=1.1
   :depends seqkit: 
   :depends snp-sites: 
   :depends tqdm: >=4.32.2
   :depends xlsxwriter: >=1.1.8
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install centreseq

   and update with::

      conda update centreseq

   or use the docker container::

      docker pull quay.io/biocontainers/centreseq:<tag>

   (see `centreseq/tags`_ for valid values for ``<tag>``)


.. |downloads_centreseq| image:: https://img.shields.io/conda/dn/bioconda/centreseq.svg?style=flat
   :target: https://anaconda.org/bioconda/centreseq
   :alt:   (downloads)
.. |docker_centreseq| image:: https://quay.io/repository/biocontainers/centreseq/status
   :target: https://quay.io/repository/biocontainers/centreseq
.. _`centreseq/tags`: https://quay.io/repository/biocontainers/centreseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/centreseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/centreseq/README.html
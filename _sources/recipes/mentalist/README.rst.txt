:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'mentalist'
.. highlight: bash

mentalist
=========

.. conda:recipe:: mentalist
   :replaces_section_title:

   The MLST pipeline developed by the PathOGiST research group.

   :homepage: https://github.com/WGS-TB/MentaLiST
   :license: MIT
   :recipe: /`mentalist <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/mentalist>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/mentalist/meta.yaml>`_

   


.. conda:package:: mentalist

   |downloads_mentalist| |docker_mentalist|

   :versions: 0.2.4-2, 0.2.4-1, 0.2.3-1, 0.2.3-0, 0.2.2-2, 0.2.2-1, 0.2.2-0, 0.2.1-3, 0.2.1-2, 0.2.1-1, 0.2.0-1, 0.2.0-0, 0.1.9-4, 0.1.9-3, 0.1.9-2, 0.1.9-1, 0.1.8-2, 0.1.8-0, 0.1.7-2, 0.1.7-0, 0.1.6-2, 0.1.6-0, 0.1.5-3, 0.1.5-1, 0.1.5-0, 0.1.4-2, 0.1.4-0, 0.1.3-3, 0.1.3-1, 0.1.3-0, 0.1.2-0
   
   :depends hdf5: >=1.10.3,<1.10.4.0a0
   :depends julia: 0.6.1 blas_openblas_202
   :depends libxml2: 
   :depends mpfr: >=3.1.5,<4.0a0
   :depends unzip: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install mentalist

   and update with::

      conda update mentalist

   or use the docker container::

      docker pull quay.io/biocontainers/mentalist:<tag>

   (see `mentalist/tags`_ for valid values for ``<tag>``)


.. |downloads_mentalist| image:: https://img.shields.io/conda/dn/bioconda/mentalist.svg?style=flat
   :target: https://anaconda.org/bioconda/mentalist
   :alt:   (downloads)
.. |docker_mentalist| image:: https://quay.io/repository/biocontainers/mentalist/status
   :target: https://quay.io/repository/biocontainers/mentalist
.. _`mentalist/tags`: https://quay.io/repository/biocontainers/mentalist?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/mentalist/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/mentalist/README.html
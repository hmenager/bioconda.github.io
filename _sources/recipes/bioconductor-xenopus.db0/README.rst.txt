:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-xenopus.db0'
.. highlight: bash

bioconductor-xenopus.db0
========================

.. conda:recipe:: bioconductor-xenopus.db0
   :replaces_section_title:

   Base annotation databases for xenopus\, intended ONLY to be used by AnnotationDbi to produce regular annotation packages.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/xenopus.db0.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-xenopus.db0 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xenopus.db0>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xenopus.db0/meta.yaml>`_

   


.. conda:package:: bioconductor-xenopus.db0

   |downloads_bioconductor-xenopus.db0| |docker_bioconductor-xenopus.db0|

   :versions: 3.8.2-1, 3.7.1-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-xenopus.db0

   and update with::

      conda update bioconductor-xenopus.db0

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-xenopus.db0:<tag>

   (see `bioconductor-xenopus.db0/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-xenopus.db0| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-xenopus.db0.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-xenopus.db0
   :alt:   (downloads)
.. |docker_bioconductor-xenopus.db0| image:: https://quay.io/repository/biocontainers/bioconductor-xenopus.db0/status
   :target: https://quay.io/repository/biocontainers/bioconductor-xenopus.db0
.. _`bioconductor-xenopus.db0/tags`: https://quay.io/repository/biocontainers/bioconductor-xenopus.db0?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-xenopus.db0/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-xenopus.db0/README.html
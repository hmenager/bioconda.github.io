:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rattus.norvegicus'
.. highlight: bash

bioconductor-rattus.norvegicus
==============================

.. conda:recipe:: bioconductor-rattus.norvegicus
   :replaces_section_title:

   Contains the Rattus.norvegicus object to access data from several related annotation packages.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/Rattus.norvegicus.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-rattus.norvegicus <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rattus.norvegicus>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rattus.norvegicus/meta.yaml>`_

   


.. conda:package:: bioconductor-rattus.norvegicus

   |downloads_bioconductor-rattus.norvegicus| |docker_bioconductor-rattus.norvegicus|

   :versions: 1.3.1-2, 1.3.1-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-go.db: >=3.8.0,<3.9.0
   :depends bioconductor-org.rn.eg.db: >=3.8.0,<3.9.0
   :depends bioconductor-organismdbi: >=1.26.0,<1.27.0
   :depends bioconductor-txdb.rnorvegicus.ucsc.rn5.refgene: >=3.4.0,<3.5.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rattus.norvegicus

   and update with::

      conda update bioconductor-rattus.norvegicus

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rattus.norvegicus:<tag>

   (see `bioconductor-rattus.norvegicus/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rattus.norvegicus| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rattus.norvegicus.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rattus.norvegicus
   :alt:   (downloads)
.. |docker_bioconductor-rattus.norvegicus| image:: https://quay.io/repository/biocontainers/bioconductor-rattus.norvegicus/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rattus.norvegicus
.. _`bioconductor-rattus.norvegicus/tags`: https://quay.io/repository/biocontainers/bioconductor-rattus.norvegicus?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rattus.norvegicus/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rattus.norvegicus/README.html
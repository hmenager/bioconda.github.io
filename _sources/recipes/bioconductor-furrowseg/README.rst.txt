:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-furrowseg'
.. highlight: bash

bioconductor-furrowseg
======================

.. conda:recipe:: bioconductor-furrowseg
   :replaces_section_title:

   Image feature data and analysis codes for the Guglielmi\, Barry et al. paper describing the application of an optogenetics tools to disrupt Drosophila embryo furrowing.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/furrowSeg.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-furrowseg <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-furrowseg>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-furrowseg/meta.yaml>`_

   


.. conda:package:: bioconductor-furrowseg

   |downloads_bioconductor-furrowseg| |docker_bioconductor-furrowseg|

   :versions: 1.12.0-1, 1.10.0-0
   
   :depends bioconductor-ebimage: >=4.26.0,<4.27.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-abind: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: 
   :depends r-locfit: 
   :depends r-tiff: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-furrowseg

   and update with::

      conda update bioconductor-furrowseg

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-furrowseg:<tag>

   (see `bioconductor-furrowseg/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-furrowseg| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-furrowseg.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-furrowseg
   :alt:   (downloads)
.. |docker_bioconductor-furrowseg| image:: https://quay.io/repository/biocontainers/bioconductor-furrowseg/status
   :target: https://quay.io/repository/biocontainers/bioconductor-furrowseg
.. _`bioconductor-furrowseg/tags`: https://quay.io/repository/biocontainers/bioconductor-furrowseg?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-furrowseg/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-furrowseg/README.html
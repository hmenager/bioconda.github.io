:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tcgacrcmirna'
.. highlight: bash

bioconductor-tcgacrcmirna
=========================

.. conda:recipe:: bioconductor-tcgacrcmirna
   :replaces_section_title:

   colorectal cancer miRNA profile provided by TCGA

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/TCGAcrcmiRNA.html
   :license: GPL-2
   :recipe: /`bioconductor-tcgacrcmirna <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tcgacrcmirna>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tcgacrcmirna/meta.yaml>`_

   


.. conda:package:: bioconductor-tcgacrcmirna

   |downloads_bioconductor-tcgacrcmirna| |docker_bioconductor-tcgacrcmirna|

   :versions: 1.4.0-1, 1.2.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tcgacrcmirna

   and update with::

      conda update bioconductor-tcgacrcmirna

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tcgacrcmirna:<tag>

   (see `bioconductor-tcgacrcmirna/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tcgacrcmirna| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tcgacrcmirna.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tcgacrcmirna
   :alt:   (downloads)
.. |docker_bioconductor-tcgacrcmirna| image:: https://quay.io/repository/biocontainers/bioconductor-tcgacrcmirna/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tcgacrcmirna
.. _`bioconductor-tcgacrcmirna/tags`: https://quay.io/repository/biocontainers/bioconductor-tcgacrcmirna?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tcgacrcmirna/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tcgacrcmirna/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-micrornaome'
.. highlight: bash

bioconductor-micrornaome
========================

.. conda:recipe:: bioconductor-micrornaome
   :replaces_section_title:

   This package provides a SummarizedExperiment object of read counts for microRNAs across tissues\, cell\-types\, and cancer cell\-lines. The read count matrix was prepared and provided by the author of the study\: Towards the human cellular microRNAome.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/microRNAome.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-micrornaome <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-micrornaome>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-micrornaome/meta.yaml>`_

   


.. conda:package:: bioconductor-micrornaome

   |downloads_bioconductor-micrornaome| |docker_bioconductor-micrornaome|

   :versions: 1.6.0-1, 1.4.0-0
   
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-micrornaome

   and update with::

      conda update bioconductor-micrornaome

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-micrornaome:<tag>

   (see `bioconductor-micrornaome/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-micrornaome| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-micrornaome.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-micrornaome
   :alt:   (downloads)
.. |docker_bioconductor-micrornaome| image:: https://quay.io/repository/biocontainers/bioconductor-micrornaome/status
   :target: https://quay.io/repository/biocontainers/bioconductor-micrornaome
.. _`bioconductor-micrornaome/tags`: https://quay.io/repository/biocontainers/bioconductor-micrornaome?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-micrornaome/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-micrornaome/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-stager'
.. highlight: bash

bioconductor-stager
===================

.. conda:recipe:: bioconductor-stager
   :replaces_section_title:

   The stageR package allows automated stage\-wise analysis of high\-throughput gene expression data. The method is published in Genome Biology at https\:\/\/genomebiology.biomedcentral.com\/articles\/10.1186\/s13059\-017\-1277\-0

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/stageR.html
   :license: GNU General Public License version 3
   :recipe: /`bioconductor-stager <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-stager>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-stager/meta.yaml>`_

   


.. conda:package:: bioconductor-stager

   |downloads_bioconductor-stager| |docker_bioconductor-stager|

   :versions: 1.6.0-1, 1.4.0-0
   
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-stager

   and update with::

      conda update bioconductor-stager

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-stager:<tag>

   (see `bioconductor-stager/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-stager| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-stager.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-stager
   :alt:   (downloads)
.. |docker_bioconductor-stager| image:: https://quay.io/repository/biocontainers/bioconductor-stager/status
   :target: https://quay.io/repository/biocontainers/bioconductor-stager
.. _`bioconductor-stager/tags`: https://quay.io/repository/biocontainers/bioconductor-stager?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-stager/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-stager/README.html
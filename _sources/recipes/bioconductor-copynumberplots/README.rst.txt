:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-copynumberplots'
.. highlight: bash

bioconductor-copynumberplots
============================

.. conda:recipe:: bioconductor-copynumberplots
   :replaces_section_title:

   CopyNumberPlots have a set of functions extending karyoploteRs functionality to create beautiful\, customizable and flexible plots of copy\-number related data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/CopyNumberPlots.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-copynumberplots <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-copynumberplots>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-copynumberplots/meta.yaml>`_

   


.. conda:package:: bioconductor-copynumberplots

   |downloads_bioconductor-copynumberplots| |docker_bioconductor-copynumberplots|

   :versions: 1.0.1-0
   
   :depends bioconductor-cn.mops: >=1.30.0,<1.31.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-karyoploter: >=1.10.0,<1.11.0
   :depends bioconductor-regioner: >=1.16.0,<1.17.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-copynumberplots

   and update with::

      conda update bioconductor-copynumberplots

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-copynumberplots:<tag>

   (see `bioconductor-copynumberplots/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-copynumberplots| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-copynumberplots.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-copynumberplots
   :alt:   (downloads)
.. |docker_bioconductor-copynumberplots| image:: https://quay.io/repository/biocontainers/bioconductor-copynumberplots/status
   :target: https://quay.io/repository/biocontainers/bioconductor-copynumberplots
.. _`bioconductor-copynumberplots/tags`: https://quay.io/repository/biocontainers/bioconductor-copynumberplots?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-copynumberplots/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-copynumberplots/README.html
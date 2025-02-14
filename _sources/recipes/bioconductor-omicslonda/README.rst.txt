:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-omicslonda'
.. highlight: bash

bioconductor-omicslonda
=======================

.. conda:recipe:: bioconductor-omicslonda
   :replaces_section_title:

   Statistical method that provides robust identification of time intervals where omics features \(such as proteomics\, lipidomics\, metabolomics\, transcriptomics\, microbiome\, as well as physiological parameters captured by wearable sensors such as heart rhythm\, body temperature\, and activity level\) are significantly different between groups.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/OmicsLonDA.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-omicslonda <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-omicslonda>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-omicslonda/meta.yaml>`_

   


.. conda:package:: bioconductor-omicslonda

   |downloads_bioconductor-omicslonda| |docker_bioconductor-omicslonda|

   :versions: 1.0.0-1
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-gss: 
   :depends r-plyr: 
   :depends r-pracma: 
   :depends r-zoo: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-omicslonda

   and update with::

      conda update bioconductor-omicslonda

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-omicslonda:<tag>

   (see `bioconductor-omicslonda/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-omicslonda| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-omicslonda.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-omicslonda
   :alt:   (downloads)
.. |docker_bioconductor-omicslonda| image:: https://quay.io/repository/biocontainers/bioconductor-omicslonda/status
   :target: https://quay.io/repository/biocontainers/bioconductor-omicslonda
.. _`bioconductor-omicslonda/tags`: https://quay.io/repository/biocontainers/bioconductor-omicslonda?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-omicslonda/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-omicslonda/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-vegamc'
.. highlight: bash

bioconductor-vegamc
===================

.. conda:recipe:: bioconductor-vegamc
   :replaces_section_title:

   This package enables the detection of driver chromosomal imbalances including loss of heterozygosity \(LOH\) from array comparative genomic hybridization \(aCGH\) data. VegaMC performs a joint segmentation of a dataset and uses a statistical framework to distinguish between driver and passenger mutation. VegaMC has been implemented so that it can be immediately integrated with the output produced by PennCNV tool. In addition\, VegaMC produces in output two web pages that allows a rapid navigation between both the detected regions and the altered genes. In the web page that summarizes the altered genes\, the link to the respective Ensembl gene web page is reported.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/VegaMC.html
   :license: GPL-2
   :recipe: /`bioconductor-vegamc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vegamc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vegamc/meta.yaml>`_
   :links: biotools: :biotools:`vegamc`, doi: :doi:`10.1093/bioinformatics/bts453`

   


.. conda:package:: bioconductor-vegamc

   |downloads_bioconductor-vegamc| |docker_bioconductor-vegamc|

   :versions: 3.22.0-1, 3.20.0-0, 3.18.0-0, 3.16.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biomart: >=2.40.0,<2.41.0
   :depends bioconductor-genoset: >=1.40.0,<1.41.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-vegamc

   and update with::

      conda update bioconductor-vegamc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-vegamc:<tag>

   (see `bioconductor-vegamc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-vegamc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-vegamc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-vegamc
   :alt:   (downloads)
.. |docker_bioconductor-vegamc| image:: https://quay.io/repository/biocontainers/bioconductor-vegamc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-vegamc
.. _`bioconductor-vegamc/tags`: https://quay.io/repository/biocontainers/bioconductor-vegamc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-vegamc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-vegamc/README.html
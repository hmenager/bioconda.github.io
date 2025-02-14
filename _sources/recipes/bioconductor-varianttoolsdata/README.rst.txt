:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-varianttoolsdata'
.. highlight: bash

bioconductor-varianttoolsdata
=============================

.. conda:recipe:: bioconductor-varianttoolsdata
   :replaces_section_title:

   Data from the sequencing of a 50\/50 mixture of HapMap trio samples NA12878 \(CEU\) and NA19240 \(YRI\)\, subset to the TP53 region.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/VariantToolsData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-varianttoolsdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-varianttoolsdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-varianttoolsdata/meta.yaml>`_

   


.. conda:package:: bioconductor-varianttoolsdata

   |downloads_bioconductor-varianttoolsdata| |docker_bioconductor-varianttoolsdata|

   :versions: 1.8.0-1, 1.6.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-varianttoolsdata

   and update with::

      conda update bioconductor-varianttoolsdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-varianttoolsdata:<tag>

   (see `bioconductor-varianttoolsdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-varianttoolsdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-varianttoolsdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-varianttoolsdata
   :alt:   (downloads)
.. |docker_bioconductor-varianttoolsdata| image:: https://quay.io/repository/biocontainers/bioconductor-varianttoolsdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-varianttoolsdata
.. _`bioconductor-varianttoolsdata/tags`: https://quay.io/repository/biocontainers/bioconductor-varianttoolsdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-varianttoolsdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-varianttoolsdata/README.html
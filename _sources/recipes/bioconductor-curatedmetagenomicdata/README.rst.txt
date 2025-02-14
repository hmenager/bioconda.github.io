:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-curatedmetagenomicdata'
.. highlight: bash

bioconductor-curatedmetagenomicdata
===================================

.. conda:recipe:: bioconductor-curatedmetagenomicdata
   :replaces_section_title:

   The curatedMetagenomicData package provides microbial taxonomic\, functional\, and gene marker abundance for samples collected from different bodysites.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/curatedMetagenomicData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-curatedmetagenomicdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-curatedmetagenomicdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-curatedmetagenomicdata/meta.yaml>`_

   


.. conda:package:: bioconductor-curatedmetagenomicdata

   |downloads_bioconductor-curatedmetagenomicdata| |docker_bioconductor-curatedmetagenomicdata|

   :versions: 1.14.1-0, 1.12.3-0, 1.10.2-0, 1.8.1-0
   
   :depends bioconductor-annotationhub: >=2.16.0,<2.17.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-experimenthub: >=1.10.0,<1.11.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: >=0.5.0
   :depends r-magrittr: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-curatedmetagenomicdata

   and update with::

      conda update bioconductor-curatedmetagenomicdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-curatedmetagenomicdata:<tag>

   (see `bioconductor-curatedmetagenomicdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-curatedmetagenomicdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-curatedmetagenomicdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-curatedmetagenomicdata
   :alt:   (downloads)
.. |docker_bioconductor-curatedmetagenomicdata| image:: https://quay.io/repository/biocontainers/bioconductor-curatedmetagenomicdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-curatedmetagenomicdata
.. _`bioconductor-curatedmetagenomicdata/tags`: https://quay.io/repository/biocontainers/bioconductor-curatedmetagenomicdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-curatedmetagenomicdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-curatedmetagenomicdata/README.html
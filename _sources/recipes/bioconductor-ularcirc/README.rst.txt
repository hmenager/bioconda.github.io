:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ularcirc'
.. highlight: bash

bioconductor-ularcirc
=====================

.. conda:recipe:: bioconductor-ularcirc
   :replaces_section_title:

   Ularcirc reads in STAR aligned splice junction files and provides visualisation and analysis tools for splicing analysis. Users can assess backsplice junctions and forward canonical junctions.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/Ularcirc.html
   :license: file LICENSE
   :recipe: /`bioconductor-ularcirc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ularcirc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ularcirc/meta.yaml>`_

   


.. conda:package:: bioconductor-ularcirc

   |downloads_bioconductor-ularcirc| |docker_bioconductor-ularcirc|

   :versions: 1.2.0-1, 1.0.0-0
   
   :depends bioconductor-annotationhub: >=2.16.0,<2.17.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomeinfodbdata: >=1.2.0,<1.3.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-mirbase.db: >=1.2.0,<1.3.0
   :depends bioconductor-sushi: >=1.22.0,<1.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: >=1.9.4
   :depends r-dt: 
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-gsubfn: 
   :depends r-httpuv: 
   :depends r-moments: 
   :depends r-shiny: 
   :depends r-shinyfiles: 
   :depends r-yaml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ularcirc

   and update with::

      conda update bioconductor-ularcirc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ularcirc:<tag>

   (see `bioconductor-ularcirc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ularcirc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ularcirc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ularcirc
   :alt:   (downloads)
.. |docker_bioconductor-ularcirc| image:: https://quay.io/repository/biocontainers/bioconductor-ularcirc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ularcirc
.. _`bioconductor-ularcirc/tags`: https://quay.io/repository/biocontainers/bioconductor-ularcirc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ularcirc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ularcirc/README.html
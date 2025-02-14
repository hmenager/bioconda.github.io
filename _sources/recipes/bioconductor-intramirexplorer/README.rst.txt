:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-intramirexplorer'
.. highlight: bash

bioconductor-intramirexplorer
=============================

.. conda:recipe:: bioconductor-intramirexplorer
   :replaces_section_title:

   Intra\-miR\-ExploreR\, an integrative miRNA target prediction bioinformatics tool\, identifies targets combining expression and biophysical interactions of a given microRNA \(miR\). Using the tool\, we have identified targets for 92 intragenic miRs in D. melanogaster\, using available microarray expression data\, from Affymetrix 1 and Affymetrix2 microarray array platforms\, providing a global perspective of intragenic miR targets in Drosophila. Predicted targets are grouped according to biological functions using the DAVID Gene Ontology tool and are ranked based on a biologically relevant scoring system\, enabling the user to identify functionally relevant targets for a given miR.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/IntramiRExploreR.html
   :license: GPL-2
   :recipe: /`bioconductor-intramirexplorer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-intramirexplorer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-intramirexplorer/meta.yaml>`_

   


.. conda:package:: bioconductor-intramirexplorer

   |downloads_bioconductor-intramirexplorer| |docker_bioconductor-intramirexplorer|

   :versions: 1.6.0-1, 1.6.0-0, 1.4.0-0
   
   :depends bioconductor-fgnet: >=3.18.0,<3.19.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-igraph: >=1.0.1
   :depends r-knitr: >=1.12.3
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-intramirexplorer

   and update with::

      conda update bioconductor-intramirexplorer

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-intramirexplorer:<tag>

   (see `bioconductor-intramirexplorer/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-intramirexplorer| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-intramirexplorer.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-intramirexplorer
   :alt:   (downloads)
.. |docker_bioconductor-intramirexplorer| image:: https://quay.io/repository/biocontainers/bioconductor-intramirexplorer/status
   :target: https://quay.io/repository/biocontainers/bioconductor-intramirexplorer
.. _`bioconductor-intramirexplorer/tags`: https://quay.io/repository/biocontainers/bioconductor-intramirexplorer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-intramirexplorer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-intramirexplorer/README.html
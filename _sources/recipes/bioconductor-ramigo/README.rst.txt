:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ramigo'
.. highlight: bash

bioconductor-ramigo
===================

.. conda:recipe:: bioconductor-ramigo
   :replaces_section_title:

   R interface sending requests to AmiGO visualize\, retrieving DAG GO trees\, parsing GraphViz DOT format files and exporting GML files for Cytoscape. Deprecated\:Also uses RCytoscape to interactively display AmiGO trees in Cytoscape.

   :homepage: http://bioconductor.org/packages/3.7/bioc/html/RamiGO.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ramigo <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ramigo>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ramigo/meta.yaml>`_
   :links: biotools: :biotools:`ramigo`

   


.. conda:package:: bioconductor-ramigo

   |downloads_bioconductor-ramigo| |docker_bioconductor-ramigo|

   :versions: 1.28.0-0, 1.23.0-0, 1.22.0-0
   
   :depends bioconductor-graph: >=1.58.0,<1.60.0
   :depends r-base: >=3.4.1,<3.4.2.0a0
   :depends r-gsubfn: 
   :depends r-igraph: 
   :depends r-png: 
   :depends r-rcurl: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ramigo

   and update with::

      conda update bioconductor-ramigo

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ramigo:<tag>

   (see `bioconductor-ramigo/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ramigo| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ramigo.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ramigo
   :alt:   (downloads)
.. |docker_bioconductor-ramigo| image:: https://quay.io/repository/biocontainers/bioconductor-ramigo/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ramigo
.. _`bioconductor-ramigo/tags`: https://quay.io/repository/biocontainers/bioconductor-ramigo?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ramigo/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ramigo/README.html
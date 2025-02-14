:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-limmagui'
.. highlight: bash

bioconductor-limmagui
=====================

.. conda:recipe:: bioconductor-limmagui
   :replaces_section_title:

   A Graphical User Interface for differential expression analysis of two\-color microarray data using the limma package.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/limmaGUI.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-limmagui <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-limmagui>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-limmagui/meta.yaml>`_

   


.. conda:package:: bioconductor-limmagui

   |downloads_bioconductor-limmagui| |docker_bioconductor-limmagui|

   :versions: 1.60.0-1, 1.60.0-0, 1.58.0-0
   
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-r2html: 
   :depends r-tkrplot: 
   :depends r-xtable: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-limmagui

   and update with::

      conda update bioconductor-limmagui

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-limmagui:<tag>

   (see `bioconductor-limmagui/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-limmagui| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-limmagui.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-limmagui
   :alt:   (downloads)
.. |docker_bioconductor-limmagui| image:: https://quay.io/repository/biocontainers/bioconductor-limmagui/status
   :target: https://quay.io/repository/biocontainers/bioconductor-limmagui
.. _`bioconductor-limmagui/tags`: https://quay.io/repository/biocontainers/bioconductor-limmagui?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-limmagui/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-limmagui/README.html
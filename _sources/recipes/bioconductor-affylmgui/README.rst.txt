:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-affylmgui'
.. highlight: bash

bioconductor-affylmgui
======================

.. conda:recipe:: bioconductor-affylmgui
   :replaces_section_title:

   A Graphical User Interface \(GUI\) for analysis of Affymetrix microarray gene expression data using the affy and limma packages.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/affylmGUI.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-affylmgui <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-affylmgui>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-affylmgui/meta.yaml>`_

   


.. conda:package:: bioconductor-affylmgui

   |downloads_bioconductor-affylmgui| |docker_bioconductor-affylmgui|

   :versions: 1.58.0-1, 1.56.0-0
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-affyio: >=1.54.0,<1.55.0
   :depends bioconductor-affyplm: >=1.60.0,<1.61.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-gcrma: >=2.56.0,<2.57.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-biocmanager: 
   :depends r-r2html: 
   :depends r-tkrplot: 
   :depends r-xtable: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-affylmgui

   and update with::

      conda update bioconductor-affylmgui

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-affylmgui:<tag>

   (see `bioconductor-affylmgui/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-affylmgui| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-affylmgui.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-affylmgui
   :alt:   (downloads)
.. |docker_bioconductor-affylmgui| image:: https://quay.io/repository/biocontainers/bioconductor-affylmgui/status
   :target: https://quay.io/repository/biocontainers/bioconductor-affylmgui
.. _`bioconductor-affylmgui/tags`: https://quay.io/repository/biocontainers/bioconductor-affylmgui?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-affylmgui/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-affylmgui/README.html
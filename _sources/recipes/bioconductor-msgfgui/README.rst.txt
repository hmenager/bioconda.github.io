:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-msgfgui'
.. highlight: bash

bioconductor-msgfgui
====================

.. conda:recipe:: bioconductor-msgfgui
   :replaces_section_title:

   This package makes it possible to perform analyses using the MSGFplus package in a GUI environment. Furthermore it enables the user to investigate the results using interactive plots\, summary statistics and filtering. Lastly it exposes the current results to another R session so the user can seamlessly integrate the gui into other workflows.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/MSGFgui.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-msgfgui <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-msgfgui>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-msgfgui/meta.yaml>`_

   


.. conda:package:: bioconductor-msgfgui

   |downloads_bioconductor-msgfgui| |docker_bioconductor-msgfgui|

   :versions: 1.16.1-0
   
   :depends bioconductor-msgfplus: >=1.16.0,<1.17.0
   :depends bioconductor-mzid: >=1.20.0,<1.21.0
   :depends bioconductor-mzr: >=2.16.0,<2.17.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-shiny: 
   :depends r-shinyfiles: >=0.4.0
   :depends r-xlsx: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-msgfgui

   and update with::

      conda update bioconductor-msgfgui

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-msgfgui:<tag>

   (see `bioconductor-msgfgui/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-msgfgui| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-msgfgui.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-msgfgui
   :alt:   (downloads)
.. |docker_bioconductor-msgfgui| image:: https://quay.io/repository/biocontainers/bioconductor-msgfgui/status
   :target: https://quay.io/repository/biocontainers/bioconductor-msgfgui
.. _`bioconductor-msgfgui/tags`: https://quay.io/repository/biocontainers/bioconductor-msgfgui?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-msgfgui/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-msgfgui/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-director'
.. highlight: bash

bioconductor-director
=====================

.. conda:recipe:: bioconductor-director
   :replaces_section_title:

   Director is an R package designed to streamline the visualization of molecular effects in regulatory cascades. It utilizes the R package htmltools and a modified Sankey plugin of the JavaScript library D3 to provide a fast and easy\, browser\-enabled solution to discovering potentially interesting downstream effects of regulatory and\/or co\-expressed molecules. The diagrams are robust\, interactive\, and packaged as highly\-portable HTML files that eliminate the need for third\-party software to view. This enables a straightforward approach for scientists to interpret the data produced\, and bioinformatics developers an alternative means to present relevant data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/Director.html
   :license: GPL-3 + file LICENSE
   :recipe: /`bioconductor-director <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-director>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-director/meta.yaml>`_
   :links: biotools: :biotools:`director`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-director

   |downloads_bioconductor-director| |docker_bioconductor-director|

   :versions: 1.10.0-1, 1.10.0-0, 1.8.0-0, 1.6.0-0, 1.4.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-htmltools: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-director

   and update with::

      conda update bioconductor-director

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-director:<tag>

   (see `bioconductor-director/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-director| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-director.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-director
   :alt:   (downloads)
.. |docker_bioconductor-director| image:: https://quay.io/repository/biocontainers/bioconductor-director/status
   :target: https://quay.io/repository/biocontainers/bioconductor-director
.. _`bioconductor-director/tags`: https://quay.io/repository/biocontainers/bioconductor-director?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-director/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-director/README.html
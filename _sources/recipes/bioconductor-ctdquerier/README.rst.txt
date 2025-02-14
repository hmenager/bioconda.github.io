:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ctdquerier'
.. highlight: bash

bioconductor-ctdquerier
=======================

.. conda:recipe:: bioconductor-ctdquerier
   :replaces_section_title:

   Package to retrieve and visualize data from the Comparative Toxicogenomics Database \(http\:\/\/ctdbase.org\/\). The downloaded data is formated as DataFrames for further downstream analyses.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/CTDquerier.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-ctdquerier <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ctdquerier>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ctdquerier/meta.yaml>`_

   


.. conda:package:: bioconductor-ctdquerier

   |downloads_bioconductor-ctdquerier| |docker_bioconductor-ctdquerier|

   :versions: 1.4.0-1, 1.2.0-0
   
   :depends bioconductor-biocfilecache: >=1.8.0,<1.9.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-gridextra: 
   :depends r-igraph: 
   :depends r-rappdirs: 
   :depends r-rcurl: 
   :depends r-stringdist: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ctdquerier

   and update with::

      conda update bioconductor-ctdquerier

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ctdquerier:<tag>

   (see `bioconductor-ctdquerier/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ctdquerier| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ctdquerier.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ctdquerier
   :alt:   (downloads)
.. |docker_bioconductor-ctdquerier| image:: https://quay.io/repository/biocontainers/bioconductor-ctdquerier/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ctdquerier
.. _`bioconductor-ctdquerier/tags`: https://quay.io/repository/biocontainers/bioconductor-ctdquerier?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ctdquerier/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ctdquerier/README.html
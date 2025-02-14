:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'dropest'
.. highlight: bash

dropest
=======

.. conda:recipe:: dropest
   :replaces_section_title:

   Pipeline for initial analysis of droplet\-based single\-cell RNA\-seq data

   :homepage: https://github.com/hms-dbmi/dropEst/
   :license: GPL3
   :recipe: /`dropest <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/dropest>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/dropest/meta.yaml>`_

   


.. conda:package:: dropest

   |downloads_dropest| |docker_dropest|

   :versions: 0.8.6-0, 0.8.5-1, 0.8.5-0
   
   :depends boost: >=1.70.0,<1.70.1.0a0
   :depends bzip2: >=1.0.8,<2.0a0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-ks: 
   :depends r-magrittr: 
   :depends r-matrix: 
   :depends r-pcapp: 
   :depends r-rcpp: 
   :depends r-rcppeigen: 
   :depends r-rcppprogress: 
   :depends r-rinside: 
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install dropest

   and update with::

      conda update dropest

   or use the docker container::

      docker pull quay.io/biocontainers/dropest:<tag>

   (see `dropest/tags`_ for valid values for ``<tag>``)


.. |downloads_dropest| image:: https://img.shields.io/conda/dn/bioconda/dropest.svg?style=flat
   :target: https://anaconda.org/bioconda/dropest
   :alt:   (downloads)
.. |docker_dropest| image:: https://quay.io/repository/biocontainers/dropest/status
   :target: https://quay.io/repository/biocontainers/dropest
.. _`dropest/tags`: https://quay.io/repository/biocontainers/dropest?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/dropest/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/dropest/README.html
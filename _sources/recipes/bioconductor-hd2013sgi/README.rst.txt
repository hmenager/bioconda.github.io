:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hd2013sgi'
.. highlight: bash

bioconductor-hd2013sgi
======================

.. conda:recipe:: bioconductor-hd2013sgi
   :replaces_section_title:

   This package contains the experimental data and a complete executable transcript \(vignette\) of the analysis of the HCT116 genetic interaction matrix presented in the paper \"Mapping genetic interactions in human cancer cells with RNAi and multiparametric phenotyping\" by C. Laufer\, B. Fischer\, M. Billmann\, W. Huber\, M. Boutros\; Nature Methods \(2013\) 10\:427\-31. doi\: 10.1038\/nmeth.2436.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/HD2013SGI.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-hd2013sgi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hd2013sgi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hd2013sgi/meta.yaml>`_

   


.. conda:package:: bioconductor-hd2013sgi

   |downloads_bioconductor-hd2013sgi| |docker_bioconductor-hd2013sgi|

   :versions: 1.24.0-1, 1.22.0-0
   
   :depends bioconductor-ebimage: >=4.26.0,<4.27.0
   :depends bioconductor-geneplotter: >=1.62.0,<1.63.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-splots: >=1.50.0,<1.51.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-gplots: 
   :depends r-lsd: 
   :depends r-rcolorbrewer: 
   :depends r-vcd: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hd2013sgi

   and update with::

      conda update bioconductor-hd2013sgi

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hd2013sgi:<tag>

   (see `bioconductor-hd2013sgi/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hd2013sgi| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hd2013sgi.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hd2013sgi
   :alt:   (downloads)
.. |docker_bioconductor-hd2013sgi| image:: https://quay.io/repository/biocontainers/bioconductor-hd2013sgi/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hd2013sgi
.. _`bioconductor-hd2013sgi/tags`: https://quay.io/repository/biocontainers/bioconductor-hd2013sgi?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hd2013sgi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hd2013sgi/README.html
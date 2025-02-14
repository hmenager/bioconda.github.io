:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-made4'
.. highlight: bash

bioconductor-made4
==================

.. conda:recipe:: bioconductor-made4
   :replaces_section_title:

   Multivariate data analysis and graphical display of microarray data. Functions include between group analysis and coinertia analysis. It contains functions that require ADE4.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/made4.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-made4 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-made4>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-made4/meta.yaml>`_
   :links: biotools: :biotools:`made4`

   


.. conda:package:: bioconductor-made4

   |downloads_bioconductor-made4| |docker_bioconductor-made4|

   :versions: 1.58.0-1, 1.58.0-0, 1.56.0-0, 1.54.0-0, 1.52.0-0, 1.50.0-0, 1.44.0-0
   
   :depends r-ade4: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-gplots: 
   :depends r-rcolorbrewer: 
   :depends r-scatterplot3d: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-made4

   and update with::

      conda update bioconductor-made4

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-made4:<tag>

   (see `bioconductor-made4/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-made4| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-made4.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-made4
   :alt:   (downloads)
.. |docker_bioconductor-made4| image:: https://quay.io/repository/biocontainers/bioconductor-made4/status
   :target: https://quay.io/repository/biocontainers/bioconductor-made4
.. _`bioconductor-made4/tags`: https://quay.io/repository/biocontainers/bioconductor-made4?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-made4/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-made4/README.html
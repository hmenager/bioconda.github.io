:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-timecourse'
.. highlight: bash

bioconductor-timecourse
=======================

.. conda:recipe:: bioconductor-timecourse
   :replaces_section_title:

   Functions for data analysis and graphical displays for developmental microarray time course data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/timecourse.html
   :license: LGPL
   :recipe: /`bioconductor-timecourse <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-timecourse>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-timecourse/meta.yaml>`_
   :links: biotools: :biotools:`timecourse`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-timecourse

   |downloads_bioconductor-timecourse| |docker_bioconductor-timecourse|

   :versions: 1.56.0-1, 1.54.0-0, 1.52.0-0, 1.50.0-0, 1.48.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-marray: >=1.62.0,<1.63.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-mass: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-timecourse

   and update with::

      conda update bioconductor-timecourse

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-timecourse:<tag>

   (see `bioconductor-timecourse/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-timecourse| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-timecourse.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-timecourse
   :alt:   (downloads)
.. |docker_bioconductor-timecourse| image:: https://quay.io/repository/biocontainers/bioconductor-timecourse/status
   :target: https://quay.io/repository/biocontainers/bioconductor-timecourse
.. _`bioconductor-timecourse/tags`: https://quay.io/repository/biocontainers/bioconductor-timecourse?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-timecourse/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-timecourse/README.html
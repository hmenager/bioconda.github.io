:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-sim'
.. highlight: bash

bioconductor-sim
================

.. conda:recipe:: bioconductor-sim
   :replaces_section_title:

   Finds associations between two human genomic datasets.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/SIM.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-sim <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sim>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sim/meta.yaml>`_
   :links: biotools: :biotools:`sim`, doi: :doi:`10.1186/1471-2105-10-203`

   


.. conda:package:: bioconductor-sim

   |downloads_bioconductor-sim| |docker_bioconductor-sim|

   :versions: 1.54.0-1, 1.52.0-1, 1.52.0-0, 1.50.0-0, 1.48.0-0
   
   :depends bioconductor-globaltest: >=5.38.0,<5.39.0
   :depends bioconductor-quantsmooth: >=1.50.0,<1.51.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-quantreg: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-sim

   and update with::

      conda update bioconductor-sim

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-sim:<tag>

   (see `bioconductor-sim/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-sim| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-sim.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-sim
   :alt:   (downloads)
.. |docker_bioconductor-sim| image:: https://quay.io/repository/biocontainers/bioconductor-sim/status
   :target: https://quay.io/repository/biocontainers/bioconductor-sim
.. _`bioconductor-sim/tags`: https://quay.io/repository/biocontainers/bioconductor-sim?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-sim/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-sim/README.html
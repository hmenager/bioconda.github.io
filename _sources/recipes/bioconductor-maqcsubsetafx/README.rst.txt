:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-maqcsubsetafx'
.. highlight: bash

bioconductor-maqcsubsetafx
==========================

.. conda:recipe:: bioconductor-maqcsubsetafx
   :replaces_section_title:

   MAQC data subset for the Affymetrix platform

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/MAQCsubsetAFX.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-maqcsubsetafx <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-maqcsubsetafx>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-maqcsubsetafx/meta.yaml>`_

   


.. conda:package:: bioconductor-maqcsubsetafx

   |downloads_bioconductor-maqcsubsetafx| |docker_bioconductor-maqcsubsetafx|

   :versions: 1.22.0-1, 1.20.0-1, 1.20.0-0
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-maqcsubsetafx

   and update with::

      conda update bioconductor-maqcsubsetafx

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-maqcsubsetafx:<tag>

   (see `bioconductor-maqcsubsetafx/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-maqcsubsetafx| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-maqcsubsetafx.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-maqcsubsetafx
   :alt:   (downloads)
.. |docker_bioconductor-maqcsubsetafx| image:: https://quay.io/repository/biocontainers/bioconductor-maqcsubsetafx/status
   :target: https://quay.io/repository/biocontainers/bioconductor-maqcsubsetafx
.. _`bioconductor-maqcsubsetafx/tags`: https://quay.io/repository/biocontainers/bioconductor-maqcsubsetafx?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-maqcsubsetafx/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-maqcsubsetafx/README.html
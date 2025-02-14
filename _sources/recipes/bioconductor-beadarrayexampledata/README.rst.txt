:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-beadarrayexampledata'
.. highlight: bash

bioconductor-beadarrayexampledata
=================================

.. conda:recipe:: bioconductor-beadarrayexampledata
   :replaces_section_title:

   An small dataset that can be used to run examples from the beadarray vignette and examples

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/beadarrayExampleData.html
   :license: GPL-2
   :recipe: /`bioconductor-beadarrayexampledata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-beadarrayexampledata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-beadarrayexampledata/meta.yaml>`_

   


.. conda:package:: bioconductor-beadarrayexampledata

   |downloads_bioconductor-beadarrayexampledata| |docker_bioconductor-beadarrayexampledata|

   :versions: 1.22.0-1, 1.20.0-0
   
   :depends bioconductor-beadarray: >=2.34.0,<2.35.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-beadarrayexampledata

   and update with::

      conda update bioconductor-beadarrayexampledata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-beadarrayexampledata:<tag>

   (see `bioconductor-beadarrayexampledata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-beadarrayexampledata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-beadarrayexampledata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-beadarrayexampledata
   :alt:   (downloads)
.. |docker_bioconductor-beadarrayexampledata| image:: https://quay.io/repository/biocontainers/bioconductor-beadarrayexampledata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-beadarrayexampledata
.. _`bioconductor-beadarrayexampledata/tags`: https://quay.io/repository/biocontainers/bioconductor-beadarrayexampledata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-beadarrayexampledata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-beadarrayexampledata/README.html
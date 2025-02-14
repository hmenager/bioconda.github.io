:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-blimatestingdata'
.. highlight: bash

bioconductor-blimatestingdata
=============================

.. conda:recipe:: bioconductor-blimatestingdata
   :replaces_section_title:

   Experiment data package. The set were prepared using microarray images of human mesenchymal cells treated with various supplements. This package is intended to provide example data to test functionality provided by blima.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/blimaTestingData.html
   :license: GPL-3
   :recipe: /`bioconductor-blimatestingdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-blimatestingdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-blimatestingdata/meta.yaml>`_

   


.. conda:package:: bioconductor-blimatestingdata

   |downloads_bioconductor-blimatestingdata| |docker_bioconductor-blimatestingdata|

   :versions: 1.4.0-1, 1.4.0-0, 1.2.0-0
   
   :depends curl: >=7.64.1,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-blimatestingdata

   and update with::

      conda update bioconductor-blimatestingdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-blimatestingdata:<tag>

   (see `bioconductor-blimatestingdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-blimatestingdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-blimatestingdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-blimatestingdata
   :alt:   (downloads)
.. |docker_bioconductor-blimatestingdata| image:: https://quay.io/repository/biocontainers/bioconductor-blimatestingdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-blimatestingdata
.. _`bioconductor-blimatestingdata/tags`: https://quay.io/repository/biocontainers/bioconductor-blimatestingdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-blimatestingdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-blimatestingdata/README.html
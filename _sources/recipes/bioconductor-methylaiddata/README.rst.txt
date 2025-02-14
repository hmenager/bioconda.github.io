:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-methylaiddata'
.. highlight: bash

bioconductor-methylaiddata
==========================

.. conda:recipe:: bioconductor-methylaiddata
   :replaces_section_title:

   A data package containing summarized Illumina 450k array data on 2800 samples and summarized EPIC data for 2620 samples. The data can be use as a background data set in the interactive application.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/MethylAidData.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-methylaiddata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-methylaiddata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-methylaiddata/meta.yaml>`_

   


.. conda:package:: bioconductor-methylaiddata

   |downloads_bioconductor-methylaiddata| |docker_bioconductor-methylaiddata|

   :versions: 1.16.0-1, 1.14.0-0
   
   :depends bioconductor-methylaid: >=1.18.0,<1.19.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-methylaiddata

   and update with::

      conda update bioconductor-methylaiddata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-methylaiddata:<tag>

   (see `bioconductor-methylaiddata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-methylaiddata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-methylaiddata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-methylaiddata
   :alt:   (downloads)
.. |docker_bioconductor-methylaiddata| image:: https://quay.io/repository/biocontainers/bioconductor-methylaiddata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-methylaiddata
.. _`bioconductor-methylaiddata/tags`: https://quay.io/repository/biocontainers/bioconductor-methylaiddata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-methylaiddata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-methylaiddata/README.html
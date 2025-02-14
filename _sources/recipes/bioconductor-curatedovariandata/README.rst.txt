:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-curatedovariandata'
.. highlight: bash

bioconductor-curatedovariandata
===============================

.. conda:recipe:: bioconductor-curatedovariandata
   :replaces_section_title:

   The curatedOvarianData package provides data for gene expression analysis in patients with ovarian cancer.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/curatedOvarianData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-curatedovariandata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-curatedovariandata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-curatedovariandata/meta.yaml>`_

   


.. conda:package:: bioconductor-curatedovariandata

   |downloads_bioconductor-curatedovariandata| |docker_bioconductor-curatedovariandata|

   :versions: 1.22.0-1, 1.20.0-0, 1.18.0-0, 1.16.0-1, 1.16.0-0, 1.14.0-0
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-curatedovariandata

   and update with::

      conda update bioconductor-curatedovariandata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-curatedovariandata:<tag>

   (see `bioconductor-curatedovariandata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-curatedovariandata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-curatedovariandata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-curatedovariandata
   :alt:   (downloads)
.. |docker_bioconductor-curatedovariandata| image:: https://quay.io/repository/biocontainers/bioconductor-curatedovariandata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-curatedovariandata
.. _`bioconductor-curatedovariandata/tags`: https://quay.io/repository/biocontainers/bioconductor-curatedovariandata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-curatedovariandata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-curatedovariandata/README.html
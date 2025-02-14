:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-prostatecancervarambally'
.. highlight: bash

bioconductor-prostatecancervarambally
=====================================

.. conda:recipe:: bioconductor-prostatecancervarambally
   :replaces_section_title:

   A Bioconductor data package for the Varambally dataset

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/prostateCancerVarambally.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-prostatecancervarambally <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-prostatecancervarambally>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-prostatecancervarambally/meta.yaml>`_

   


.. conda:package:: bioconductor-prostatecancervarambally

   |downloads_bioconductor-prostatecancervarambally| |docker_bioconductor-prostatecancervarambally|

   :versions: 1.12.0-1, 1.10.0-1, 1.10.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-prostatecancervarambally

   and update with::

      conda update bioconductor-prostatecancervarambally

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-prostatecancervarambally:<tag>

   (see `bioconductor-prostatecancervarambally/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-prostatecancervarambally| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-prostatecancervarambally.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-prostatecancervarambally
   :alt:   (downloads)
.. |docker_bioconductor-prostatecancervarambally| image:: https://quay.io/repository/biocontainers/bioconductor-prostatecancervarambally/status
   :target: https://quay.io/repository/biocontainers/bioconductor-prostatecancervarambally
.. _`bioconductor-prostatecancervarambally/tags`: https://quay.io/repository/biocontainers/bioconductor-prostatecancervarambally?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-prostatecancervarambally/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-prostatecancervarambally/README.html
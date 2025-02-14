:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-jaspar2018'
.. highlight: bash

bioconductor-jaspar2018
=======================

.. conda:recipe:: bioconductor-jaspar2018
   :replaces_section_title:

   Data package for JASPAR 2018. To search this databases\, please use the package TFBSTools \(\>\= 1.15.6\).

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/JASPAR2018.html
   :license: GPL-2
   :recipe: /`bioconductor-jaspar2018 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-jaspar2018>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-jaspar2018/meta.yaml>`_

   


.. conda:package:: bioconductor-jaspar2018

   |downloads_bioconductor-jaspar2018| |docker_bioconductor-jaspar2018|

   :versions: 1.1.1-2, 1.1.1-1, 1.1.1-0, 1.0.0-1, 1.0.0-0, 0.99.2-0
   
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-jaspar2018

   and update with::

      conda update bioconductor-jaspar2018

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-jaspar2018:<tag>

   (see `bioconductor-jaspar2018/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-jaspar2018| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-jaspar2018.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-jaspar2018
   :alt:   (downloads)
.. |docker_bioconductor-jaspar2018| image:: https://quay.io/repository/biocontainers/bioconductor-jaspar2018/status
   :target: https://quay.io/repository/biocontainers/bioconductor-jaspar2018
.. _`bioconductor-jaspar2018/tags`: https://quay.io/repository/biocontainers/bioconductor-jaspar2018?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-jaspar2018/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-jaspar2018/README.html
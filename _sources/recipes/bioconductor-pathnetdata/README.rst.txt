:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pathnetdata'
.. highlight: bash

bioconductor-pathnetdata
========================

.. conda:recipe:: bioconductor-pathnetdata
   :replaces_section_title:

   This package contains the data employed in the vignette of the PathNet package. These data belong to the following publication\: PathNet\: A tool for pathway analysis using topological information. Dutta B\, Wallqvist A\, and Reifman J.\, Source Code for Biology and Medicine 2012 Sep 24\;7\(1\)\:10.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/PathNetData.html
   :license: GPL-3
   :recipe: /`bioconductor-pathnetdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pathnetdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pathnetdata/meta.yaml>`_

   


.. conda:package:: bioconductor-pathnetdata

   |downloads_bioconductor-pathnetdata| |docker_bioconductor-pathnetdata|

   :versions: 1.20.0-1, 1.20.0-0, 1.18.0-0
   
   :depends curl: >=7.65.2,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pathnetdata

   and update with::

      conda update bioconductor-pathnetdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pathnetdata:<tag>

   (see `bioconductor-pathnetdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pathnetdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pathnetdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pathnetdata
   :alt:   (downloads)
.. |docker_bioconductor-pathnetdata| image:: https://quay.io/repository/biocontainers/bioconductor-pathnetdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pathnetdata
.. _`bioconductor-pathnetdata/tags`: https://quay.io/repository/biocontainers/bioconductor-pathnetdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pathnetdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pathnetdata/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-causalr'
.. highlight: bash

bioconductor-causalr
====================

.. conda:recipe:: bioconductor-causalr
   :replaces_section_title:

   Causal network analysis methods for regulator prediction and network reconstruction from genome scale data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/CausalR.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-causalr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-causalr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-causalr/meta.yaml>`_
   :links: biotools: :biotools:`causalr`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-causalr

   |downloads_bioconductor-causalr| |docker_bioconductor-causalr|

   :versions: 1.16.0-1, 1.16.0-0, 1.14.1-1, 1.12.0-0, 1.10.0-0, 1.8.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-igraph: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-causalr

   and update with::

      conda update bioconductor-causalr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-causalr:<tag>

   (see `bioconductor-causalr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-causalr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-causalr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-causalr
   :alt:   (downloads)
.. |docker_bioconductor-causalr| image:: https://quay.io/repository/biocontainers/bioconductor-causalr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-causalr
.. _`bioconductor-causalr/tags`: https://quay.io/repository/biocontainers/bioconductor-causalr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-causalr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-causalr/README.html
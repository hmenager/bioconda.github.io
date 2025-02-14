:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pcxn'
.. highlight: bash

bioconductor-pcxn
=================

.. conda:recipe:: bioconductor-pcxn
   :replaces_section_title:

   Discover the correlated pathways\/gene sets of a single pathway\/gene set or discover correlation relationships among multiple pathways\/gene sets. Draw a heatmap or create a network of your query and extract members of each pathway\/gene set found in the available collections \(MSigDB H hallmark\, MSigDB C2 Canonical pathways\, MSigDB C5 GO BP and Pathprint\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/pcxn.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-pcxn <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pcxn>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pcxn/meta.yaml>`_

   


.. conda:package:: bioconductor-pcxn

   |downloads_bioconductor-pcxn| |docker_bioconductor-pcxn|

   :versions: 2.6.0-1, 2.6.0-0, 2.4.0-0
   
   :depends bioconductor-pcxndata: >=2.6.0,<2.7.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-pheatmap: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pcxn

   and update with::

      conda update bioconductor-pcxn

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pcxn:<tag>

   (see `bioconductor-pcxn/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pcxn| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pcxn.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pcxn
   :alt:   (downloads)
.. |docker_bioconductor-pcxn| image:: https://quay.io/repository/biocontainers/bioconductor-pcxn/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pcxn
.. _`bioconductor-pcxn/tags`: https://quay.io/repository/biocontainers/bioconductor-pcxn?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pcxn/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pcxn/README.html
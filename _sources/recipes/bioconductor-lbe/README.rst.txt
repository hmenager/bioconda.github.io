:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-lbe'
.. highlight: bash

bioconductor-lbe
================

.. conda:recipe:: bioconductor-lbe
   :replaces_section_title:

   LBE is an efficient procedure for estimating the proportion of true null hypotheses\, the false discovery rate \(and so the q\-values\) in the framework of estimating procedures based on the marginal distribution of the p\-values without assumption for the alternative hypothesis.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/LBE.html
   :license: GPL-2
   :recipe: /`bioconductor-lbe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-lbe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-lbe/meta.yaml>`_
   :links: biotools: :biotools:`lbe`, doi: :doi:`10.1093/bioinformatics/bti063`

   


.. conda:package:: bioconductor-lbe

   |downloads_bioconductor-lbe| |docker_bioconductor-lbe|

   :versions: 1.52.0-1, 1.52.0-0, 1.50.0-0, 1.48.0-0, 1.46.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-lbe

   and update with::

      conda update bioconductor-lbe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-lbe:<tag>

   (see `bioconductor-lbe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-lbe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-lbe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-lbe
   :alt:   (downloads)
.. |docker_bioconductor-lbe| image:: https://quay.io/repository/biocontainers/bioconductor-lbe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-lbe
.. _`bioconductor-lbe/tags`: https://quay.io/repository/biocontainers/bioconductor-lbe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-lbe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-lbe/README.html
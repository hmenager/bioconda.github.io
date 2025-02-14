:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-slqpcr'
.. highlight: bash

bioconductor-slqpcr
===================

.. conda:recipe:: bioconductor-slqpcr
   :replaces_section_title:

   Functions for analysis of real\-time quantitative PCR data at SIRS\-Lab GmbH

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/SLqPCR.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-slqpcr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-slqpcr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-slqpcr/meta.yaml>`_
   :links: biotools: :biotools:`slqpcr`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-slqpcr

   |downloads_bioconductor-slqpcr| |docker_bioconductor-slqpcr|

   :versions: 1.50.0-1, 1.50.0-0, 1.48.0-0, 1.46.0-0, 1.44.0-0, 1.42.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-slqpcr

   and update with::

      conda update bioconductor-slqpcr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-slqpcr:<tag>

   (see `bioconductor-slqpcr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-slqpcr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-slqpcr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-slqpcr
   :alt:   (downloads)
.. |docker_bioconductor-slqpcr| image:: https://quay.io/repository/biocontainers/bioconductor-slqpcr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-slqpcr
.. _`bioconductor-slqpcr/tags`: https://quay.io/repository/biocontainers/bioconductor-slqpcr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-slqpcr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-slqpcr/README.html
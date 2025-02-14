:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-s4vectors'
.. highlight: bash

bioconductor-s4vectors
======================

.. conda:recipe:: bioconductor-s4vectors
   :replaces_section_title:

   The S4Vectors package defines the Vector and List virtual classes and a set of generic functions that extend the semantic of ordinary vectors and lists in R. Package developers can easily implement vector\-like or list\-like objects as concrete subclasses of Vector or List. In addition\, a few low\-level concrete subclasses of general interest \(e.g. DataFrame\, Rle\, and Hits\) are implemented in the S4Vectors package itself \(many more are implemented in the IRanges package and in other Bioconductor infrastructure packages\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/S4Vectors.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-s4vectors <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-s4vectors>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-s4vectors/meta.yaml>`_
   :links: biotools: :biotools:`s4vectors`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-s4vectors

   |downloads_bioconductor-s4vectors| |docker_bioconductor-s4vectors|

   :versions: 0.22.0-1, 0.20.1-0, 0.18.3-0, 0.16.0-0, 0.14.7-0, 0.12.2-0, 0.12.0-0, 0.10.3-0, 0.9.0-0, 0.8.11-1, 0.8.11-0, 0.8.7-0, 0.8.5-0, 0.8.1-0, 0.8.0-0, 0.6.6-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-s4vectors

   and update with::

      conda update bioconductor-s4vectors

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-s4vectors:<tag>

   (see `bioconductor-s4vectors/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-s4vectors| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-s4vectors.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-s4vectors
   :alt:   (downloads)
.. |docker_bioconductor-s4vectors| image:: https://quay.io/repository/biocontainers/bioconductor-s4vectors/status
   :target: https://quay.io/repository/biocontainers/bioconductor-s4vectors
.. _`bioconductor-s4vectors/tags`: https://quay.io/repository/biocontainers/bioconductor-s4vectors?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-s4vectors/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-s4vectors/README.html
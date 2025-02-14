:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-structstrings'
.. highlight: bash

bioconductor-structstrings
==========================

.. conda:recipe:: bioconductor-structstrings
   :replaces_section_title:

   The Structstrings package implements the widely used dot bracket annotation for storing base pairing information in structured RNA. Structstrings uses the infrastructure provided by the Biostrings package and derives the DotBracketString and related classes from the BString class. From these\, base pair tables can be produced for in depth analysis. In addition\, the loop indices of the base pairs can be retrieved as well. For better efficiency\, information conversion is implemented in C\, inspired to a large extend by the ViennaRNA package.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/Structstrings.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-structstrings <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-structstrings>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-structstrings/meta.yaml>`_

   


.. conda:package:: bioconductor-structstrings

   |downloads_bioconductor-structstrings| |docker_bioconductor-structstrings|

   :versions: 1.0.3-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-xvector: >=0.24.0,<0.25.0
   :depends libgcc-ng: >=7.3.0
   :depends r-assertive: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-stringi: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-structstrings

   and update with::

      conda update bioconductor-structstrings

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-structstrings:<tag>

   (see `bioconductor-structstrings/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-structstrings| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-structstrings.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-structstrings
   :alt:   (downloads)
.. |docker_bioconductor-structstrings| image:: https://quay.io/repository/biocontainers/bioconductor-structstrings/status
   :target: https://quay.io/repository/biocontainers/bioconductor-structstrings
.. _`bioconductor-structstrings/tags`: https://quay.io/repository/biocontainers/bioconductor-structstrings?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-structstrings/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-structstrings/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-coverageview'
.. highlight: bash

bioconductor-coverageview
=========================

.. conda:recipe:: bioconductor-coverageview
   :replaces_section_title:

   This package provides a framework for the visualization of genome coverage profiles. It can be used for ChIP\-seq experiments\, but it can be also used for genome\-wide nucleosome positioning experiments or other experiment types where it is important to have a framework in order to inspect how the coverage distributed across the genome

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/CoverageView.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-coverageview <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-coverageview>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-coverageview/meta.yaml>`_

   


.. conda:package:: bioconductor-coverageview

   |downloads_bioconductor-coverageview| |docker_bioconductor-coverageview|

   :versions: 1.22.0-1, 1.20.0-0
   
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-coverageview

   and update with::

      conda update bioconductor-coverageview

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-coverageview:<tag>

   (see `bioconductor-coverageview/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-coverageview| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-coverageview.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-coverageview
   :alt:   (downloads)
.. |docker_bioconductor-coverageview| image:: https://quay.io/repository/biocontainers/bioconductor-coverageview/status
   :target: https://quay.io/repository/biocontainers/bioconductor-coverageview
.. _`bioconductor-coverageview/tags`: https://quay.io/repository/biocontainers/bioconductor-coverageview?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-coverageview/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-coverageview/README.html
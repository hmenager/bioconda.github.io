:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gseabase'
.. highlight: bash

bioconductor-gseabase
=====================

.. conda:recipe:: bioconductor-gseabase
   :replaces_section_title:

   This package provides classes and methods to support Gene Set Enrichment Analysis \(GSEA\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/GSEABase.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-gseabase <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gseabase>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gseabase/meta.yaml>`_
   :links: biotools: :biotools:`gseabase`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-gseabase

   |downloads_bioconductor-gseabase| |docker_bioconductor-gseabase|

   :versions: 1.46.0-1, 1.44.0-0, 1.42.0-0, 1.40.0-0, 1.38.2-0, 1.34.1-0, 1.32.0-0
   
   :depends bioconductor-annotate: >=1.62.0,<1.63.0
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gseabase

   and update with::

      conda update bioconductor-gseabase

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gseabase:<tag>

   (see `bioconductor-gseabase/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gseabase| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gseabase.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gseabase
   :alt:   (downloads)
.. |docker_bioconductor-gseabase| image:: https://quay.io/repository/biocontainers/bioconductor-gseabase/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gseabase
.. _`bioconductor-gseabase/tags`: https://quay.io/repository/biocontainers/bioconductor-gseabase?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gseabase/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gseabase/README.html
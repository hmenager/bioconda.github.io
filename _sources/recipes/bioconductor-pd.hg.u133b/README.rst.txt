:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pd.hg.u133b'
.. highlight: bash

bioconductor-pd.hg.u133b
========================

.. conda:recipe:: bioconductor-pd.hg.u133b
   :replaces_section_title:

   Platform Design Info for The Manufacturer\'s Name HG\-U133B

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/pd.hg.u133b.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-pd.hg.u133b <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.hg.u133b>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.hg.u133b/meta.yaml>`_

   


.. conda:package:: bioconductor-pd.hg.u133b

   |downloads_bioconductor-pd.hg.u133b| |docker_bioconductor-pd.hg.u133b|

   :versions: 3.12.0-2, 3.12.0-0
   
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-oligo: >=1.48.0,<1.49.0
   :depends bioconductor-oligoclasses: >=1.46.0,<1.47.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dbi: >=0.3.1
   :depends r-rsqlite: >=1.0.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pd.hg.u133b

   and update with::

      conda update bioconductor-pd.hg.u133b

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pd.hg.u133b:<tag>

   (see `bioconductor-pd.hg.u133b/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pd.hg.u133b| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pd.hg.u133b.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pd.hg.u133b
   :alt:   (downloads)
.. |docker_bioconductor-pd.hg.u133b| image:: https://quay.io/repository/biocontainers/bioconductor-pd.hg.u133b/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pd.hg.u133b
.. _`bioconductor-pd.hg.u133b/tags`: https://quay.io/repository/biocontainers/bioconductor-pd.hg.u133b?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pd.hg.u133b/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pd.hg.u133b/README.html
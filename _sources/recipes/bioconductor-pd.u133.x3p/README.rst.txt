:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pd.u133.x3p'
.. highlight: bash

bioconductor-pd.u133.x3p
========================

.. conda:recipe:: bioconductor-pd.u133.x3p
   :replaces_section_title:

   Platform Design Info for The Manufacturer\'s Name U133\_X3P

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/pd.u133.x3p.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-pd.u133.x3p <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.u133.x3p>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.u133.x3p/meta.yaml>`_

   


.. conda:package:: bioconductor-pd.u133.x3p

   |downloads_bioconductor-pd.u133.x3p| |docker_bioconductor-pd.u133.x3p|

   :versions: 3.12.0-3, 3.12.0-1, 3.12.0-0
   
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

      conda install bioconductor-pd.u133.x3p

   and update with::

      conda update bioconductor-pd.u133.x3p

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pd.u133.x3p:<tag>

   (see `bioconductor-pd.u133.x3p/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pd.u133.x3p| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pd.u133.x3p.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pd.u133.x3p
   :alt:   (downloads)
.. |docker_bioconductor-pd.u133.x3p| image:: https://quay.io/repository/biocontainers/bioconductor-pd.u133.x3p/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pd.u133.x3p
.. _`bioconductor-pd.u133.x3p/tags`: https://quay.io/repository/biocontainers/bioconductor-pd.u133.x3p?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pd.u133.x3p/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pd.u133.x3p/README.html
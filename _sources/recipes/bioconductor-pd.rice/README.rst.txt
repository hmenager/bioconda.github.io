:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pd.rice'
.. highlight: bash

bioconductor-pd.rice
====================

.. conda:recipe:: bioconductor-pd.rice
   :replaces_section_title:

   Platform Design Info for The Manufacturer\'s Name Rice

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/pd.rice.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-pd.rice <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.rice>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.rice/meta.yaml>`_

   


.. conda:package:: bioconductor-pd.rice

   |downloads_bioconductor-pd.rice| |docker_bioconductor-pd.rice|

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

      conda install bioconductor-pd.rice

   and update with::

      conda update bioconductor-pd.rice

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pd.rice:<tag>

   (see `bioconductor-pd.rice/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pd.rice| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pd.rice.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pd.rice
   :alt:   (downloads)
.. |docker_bioconductor-pd.rice| image:: https://quay.io/repository/biocontainers/bioconductor-pd.rice/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pd.rice
.. _`bioconductor-pd.rice/tags`: https://quay.io/repository/biocontainers/bioconductor-pd.rice?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pd.rice/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pd.rice/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-poplarcdf'
.. highlight: bash

bioconductor-poplarcdf
======================

.. conda:recipe:: bioconductor-poplarcdf
   :replaces_section_title:

   A package containing an environment representing the Poplar.cdf file.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/poplarcdf.html
   :license: LGPL
   :recipe: /`bioconductor-poplarcdf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-poplarcdf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-poplarcdf/meta.yaml>`_

   


.. conda:package:: bioconductor-poplarcdf

   |downloads_bioconductor-poplarcdf| |docker_bioconductor-poplarcdf|

   :versions: 2.18.0-2, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-poplarcdf

   and update with::

      conda update bioconductor-poplarcdf

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-poplarcdf:<tag>

   (see `bioconductor-poplarcdf/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-poplarcdf| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-poplarcdf.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-poplarcdf
   :alt:   (downloads)
.. |docker_bioconductor-poplarcdf| image:: https://quay.io/repository/biocontainers/bioconductor-poplarcdf/status
   :target: https://quay.io/repository/biocontainers/bioconductor-poplarcdf
.. _`bioconductor-poplarcdf/tags`: https://quay.io/repository/biocontainers/bioconductor-poplarcdf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-poplarcdf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-poplarcdf/README.html
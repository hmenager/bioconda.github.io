:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ctc'
.. highlight: bash

bioconductor-ctc
================

.. conda:recipe:: bioconductor-ctc
   :replaces_section_title:

   Tools for export and import classification trees and clusters to other programs

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ctc.html
   :license: GPL-2
   :recipe: /`bioconductor-ctc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ctc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ctc/meta.yaml>`_
   :links: biotools: :biotools:`ctc`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-ctc

   |downloads_bioconductor-ctc| |docker_bioconductor-ctc|

   :versions: 1.58.0-1, 1.58.0-0, 1.56.0-0, 1.54.0-0, 1.52.0-0
   
   :depends r-amap: 
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ctc

   and update with::

      conda update bioconductor-ctc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ctc:<tag>

   (see `bioconductor-ctc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ctc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ctc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ctc
   :alt:   (downloads)
.. |docker_bioconductor-ctc| image:: https://quay.io/repository/biocontainers/bioconductor-ctc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ctc
.. _`bioconductor-ctc/tags`: https://quay.io/repository/biocontainers/bioconductor-ctc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ctc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ctc/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bgafun'
.. highlight: bash

bioconductor-bgafun
===================

.. conda:recipe:: bioconductor-bgafun
   :replaces_section_title:

   A method to identify specifity determining residues in protein families using Between Group Analysis

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/bgafun.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-bgafun <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bgafun>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bgafun/meta.yaml>`_
   :links: biotools: :biotools:`bgafun`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-bgafun

   |downloads_bioconductor-bgafun| |docker_bioconductor-bgafun|

   :versions: 1.46.0-1, 1.46.0-0, 1.44.0-0, 1.42.0-0, 1.40.0-0, 1.38.0-0
   
   :depends bioconductor-made4: >=1.58.0,<1.59.0
   :depends r-ade4: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-seqinr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bgafun

   and update with::

      conda update bioconductor-bgafun

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bgafun:<tag>

   (see `bioconductor-bgafun/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bgafun| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bgafun.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bgafun
   :alt:   (downloads)
.. |docker_bioconductor-bgafun| image:: https://quay.io/repository/biocontainers/bioconductor-bgafun/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bgafun
.. _`bioconductor-bgafun/tags`: https://quay.io/repository/biocontainers/bioconductor-bgafun?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bgafun/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bgafun/README.html
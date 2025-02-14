:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-antiprofiles'
.. highlight: bash

bioconductor-antiprofiles
=========================

.. conda:recipe:: bioconductor-antiprofiles
   :replaces_section_title:

   Implements gene expression anti\-profiles as described in Corrada Bravo et al.\, BMC Bioinformatics 2012\, 13\:272 doi\:10.1186\/1471\-2105\-13\-272.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/antiProfiles.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-antiprofiles <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-antiprofiles>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-antiprofiles/meta.yaml>`_
   :links: biotools: :biotools:`antiprofiles`, doi: :doi:`10.1186/1471-2105-13-272`

   


.. conda:package:: bioconductor-antiprofiles

   |downloads_bioconductor-antiprofiles| |docker_bioconductor-antiprofiles|

   :versions: 1.24.0-1, 1.24.0-0, 1.22.0-0, 1.20.0-0, 1.18.0-0, 1.16.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-locfit: >=1.5
   :depends r-matrixstats: >=0.50.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-antiprofiles

   and update with::

      conda update bioconductor-antiprofiles

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-antiprofiles:<tag>

   (see `bioconductor-antiprofiles/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-antiprofiles| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-antiprofiles.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-antiprofiles
   :alt:   (downloads)
.. |docker_bioconductor-antiprofiles| image:: https://quay.io/repository/biocontainers/bioconductor-antiprofiles/status
   :target: https://quay.io/repository/biocontainers/bioconductor-antiprofiles
.. _`bioconductor-antiprofiles/tags`: https://quay.io/repository/biocontainers/bioconductor-antiprofiles?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-antiprofiles/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-antiprofiles/README.html
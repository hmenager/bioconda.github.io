:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-spectraltad'
.. highlight: bash

bioconductor-spectraltad
========================

.. conda:recipe:: bioconductor-spectraltad
   :replaces_section_title:

   SpectralTAD is an R package designed to identify Topologically Associated Domains \(TADs\) from Hi\-C contact matrices. It uses a modified version of spectral clustering that uses a sliding window to quickly detect TADs. The function works on a range of different formats of contact matrices and returns a bed file of TAD coordinates. The method does not require users to adjust any parameters to work and gives them control over the number of hierarchical levels to be returned.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/SpectralTAD.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-spectraltad <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spectraltad>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spectraltad/meta.yaml>`_

   


.. conda:package:: bioconductor-spectraltad

   |downloads_bioconductor-spectraltad| |docker_bioconductor-spectraltad|

   :versions: 1.0.0-1
   
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-hiccompare: >=1.6.0,<1.7.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cluster: 
   :depends r-dplyr: 
   :depends r-magrittr: 
   :depends r-matrix: 
   :depends r-primme: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-spectraltad

   and update with::

      conda update bioconductor-spectraltad

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-spectraltad:<tag>

   (see `bioconductor-spectraltad/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-spectraltad| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-spectraltad.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-spectraltad
   :alt:   (downloads)
.. |docker_bioconductor-spectraltad| image:: https://quay.io/repository/biocontainers/bioconductor-spectraltad/status
   :target: https://quay.io/repository/biocontainers/bioconductor-spectraltad
.. _`bioconductor-spectraltad/tags`: https://quay.io/repository/biocontainers/bioconductor-spectraltad?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-spectraltad/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-spectraltad/README.html
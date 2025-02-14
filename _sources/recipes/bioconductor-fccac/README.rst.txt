:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-fccac'
.. highlight: bash

bioconductor-fccac
==================

.. conda:recipe:: bioconductor-fccac
   :replaces_section_title:

   An application of functional canonical correlation analysis to assess covariance of nucleic acid sequencing datasets such as chromatin immunoprecipitation followed by deep sequencing \(ChIP\-seq\). The package can be used as well with other types of sequencing data such as neMeRIP\-seq \(PMID\: 29489750\) or with single cell RNA\-seq or epigenome data provided in bigWig format.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/fCCAC.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-fccac <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fccac>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fccac/meta.yaml>`_
   :links: biotools: :biotools:`fccac`

   


.. conda:package:: bioconductor-fccac

   |downloads_bioconductor-fccac| |docker_bioconductor-fccac|

   :versions: 1.10.0-1, 1.8.0-0, 1.6.0-0, 1.2.0-0
   
   :depends bioconductor-complexheatmap: >=2.0.0,<2.1.0
   :depends bioconductor-genomation: >=1.16.0,<1.17.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-fda: 
   :depends r-ggplot2: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-fccac

   and update with::

      conda update bioconductor-fccac

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-fccac:<tag>

   (see `bioconductor-fccac/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-fccac| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-fccac.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-fccac
   :alt:   (downloads)
.. |docker_bioconductor-fccac| image:: https://quay.io/repository/biocontainers/bioconductor-fccac/status
   :target: https://quay.io/repository/biocontainers/bioconductor-fccac
.. _`bioconductor-fccac/tags`: https://quay.io/repository/biocontainers/bioconductor-fccac?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-fccac/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-fccac/README.html
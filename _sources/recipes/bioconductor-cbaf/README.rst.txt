:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cbaf'
.. highlight: bash

bioconductor-cbaf
=================

.. conda:recipe:: bioconductor-cbaf
   :replaces_section_title:

   This package contains functions that allow analysing and comparing various gene groups from different cancers\/cancer subgroups easily. So far\, it is compatible with RNA\-seq\, microRNA\-seq\, microarray and methylation datasets that are stored on cbioportal.org.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/cbaf.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-cbaf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cbaf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cbaf/meta.yaml>`_

   


.. conda:package:: bioconductor-cbaf

   |downloads_bioconductor-cbaf| |docker_bioconductor-cbaf|

   :versions: 1.6.0-1, 1.4.0-0
   
   :depends bioconductor-biocfilecache: >=1.8.0,<1.9.0
   :depends bioconductor-genefilter: >=1.66.0,<1.67.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cgdsr: 
   :depends r-gplots: 
   :depends r-rcolorbrewer: 
   :depends r-xlsx: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cbaf

   and update with::

      conda update bioconductor-cbaf

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cbaf:<tag>

   (see `bioconductor-cbaf/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cbaf| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cbaf.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cbaf
   :alt:   (downloads)
.. |docker_bioconductor-cbaf| image:: https://quay.io/repository/biocontainers/bioconductor-cbaf/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cbaf
.. _`bioconductor-cbaf/tags`: https://quay.io/repository/biocontainers/bioconductor-cbaf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cbaf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cbaf/README.html
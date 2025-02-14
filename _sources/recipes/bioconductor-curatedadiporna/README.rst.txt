:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-curatedadiporna'
.. highlight: bash

bioconductor-curatedadiporna
============================

.. conda:recipe:: bioconductor-curatedadiporna
   :replaces_section_title:

   A curated dataset of RNA\-Seq samples. The samples are MDI\-induced pre\-phagocytes \(3T3\-L1\) at different time points\/stage of differentiation. The package document the data collection\, pre\-processing and processing. In addition to the documentation\, the package contains the scripts that was used to generated the data.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/curatedAdipoRNA.html
   :license: GPL-3
   :recipe: /`bioconductor-curatedadiporna <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-curatedadiporna>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-curatedadiporna/meta.yaml>`_

   


.. conda:package:: bioconductor-curatedadiporna

   |downloads_bioconductor-curatedadiporna| |docker_bioconductor-curatedadiporna|

   :versions: 1.0.0-1
   
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-curatedadiporna

   and update with::

      conda update bioconductor-curatedadiporna

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-curatedadiporna:<tag>

   (see `bioconductor-curatedadiporna/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-curatedadiporna| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-curatedadiporna.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-curatedadiporna
   :alt:   (downloads)
.. |docker_bioconductor-curatedadiporna| image:: https://quay.io/repository/biocontainers/bioconductor-curatedadiporna/status
   :target: https://quay.io/repository/biocontainers/bioconductor-curatedadiporna
.. _`bioconductor-curatedadiporna/tags`: https://quay.io/repository/biocontainers/bioconductor-curatedadiporna?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-curatedadiporna/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-curatedadiporna/README.html
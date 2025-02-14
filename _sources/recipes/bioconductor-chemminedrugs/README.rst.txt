:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chemminedrugs'
.. highlight: bash

bioconductor-chemminedrugs
==========================

.. conda:recipe:: bioconductor-chemminedrugs
   :replaces_section_title:

   An annotation package for use with ChemmineR. This package includes data from DrugBank. DUD data can be downloaded using the \"DUD\(\)\" function in ChemmineR.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/ChemmineDrugs.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-chemminedrugs <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chemminedrugs>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chemminedrugs/meta.yaml>`_

   


.. conda:package:: bioconductor-chemminedrugs

   |downloads_bioconductor-chemminedrugs| |docker_bioconductor-chemminedrugs|

   :versions: 1.0.2-2, 1.0.2-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-chemminer: >=3.36.0,<3.37.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-rsqlite: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chemminedrugs

   and update with::

      conda update bioconductor-chemminedrugs

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chemminedrugs:<tag>

   (see `bioconductor-chemminedrugs/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chemminedrugs| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chemminedrugs.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chemminedrugs
   :alt:   (downloads)
.. |docker_bioconductor-chemminedrugs| image:: https://quay.io/repository/biocontainers/bioconductor-chemminedrugs/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chemminedrugs
.. _`bioconductor-chemminedrugs/tags`: https://quay.io/repository/biocontainers/bioconductor-chemminedrugs?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chemminedrugs/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chemminedrugs/README.html
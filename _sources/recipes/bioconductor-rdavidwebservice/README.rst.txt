:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rdavidwebservice'
.. highlight: bash

bioconductor-rdavidwebservice
=============================

.. conda:recipe:: bioconductor-rdavidwebservice
   :replaces_section_title:

   Tools for retrieving data from the Database for Annotation\, Visualization and Integrated Discovery \(DAVID\) using Web Services into R objects. This package offers the main functionalities of DAVID website including\: i\) user friendly connectivity to upload gene\/background list\/s\, change gene\/background position\, select current specie\/s\, select annotations\, etc. ii\) Reports of the submitted Gene List\, Annotation Category Summary\, Gene\/Term Clusters\, Functional Annotation Chart\, Functional Annotation Table

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/RDAVIDWebService.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-rdavidwebservice <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rdavidwebservice>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rdavidwebservice/meta.yaml>`_

   


.. conda:package:: bioconductor-rdavidwebservice

   |downloads_bioconductor-rdavidwebservice| |docker_bioconductor-rdavidwebservice|

   :versions: 1.22.0-1, 1.20.0-0
   
   :depends bioconductor-category: >=2.50.0,<2.51.0
   :depends bioconductor-go.db: >=3.8.0,<3.9.0
   :depends bioconductor-gostats: >=2.50.0,<2.51.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-rbgl: >=1.60.0,<1.61.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-rjava: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rdavidwebservice

   and update with::

      conda update bioconductor-rdavidwebservice

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rdavidwebservice:<tag>

   (see `bioconductor-rdavidwebservice/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rdavidwebservice| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rdavidwebservice.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rdavidwebservice
   :alt:   (downloads)
.. |docker_bioconductor-rdavidwebservice| image:: https://quay.io/repository/biocontainers/bioconductor-rdavidwebservice/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rdavidwebservice
.. _`bioconductor-rdavidwebservice/tags`: https://quay.io/repository/biocontainers/bioconductor-rdavidwebservice?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rdavidwebservice/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rdavidwebservice/README.html
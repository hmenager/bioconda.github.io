:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-diggit'
.. highlight: bash

bioconductor-diggit
===================

.. conda:recipe:: bioconductor-diggit
   :replaces_section_title:

   Inference of Genetic Variants Driving Cellullar Phenotypes by the DIGGIT algorithm

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/diggit.html
   :license: file LICENSE
   :recipe: /`bioconductor-diggit <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-diggit>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-diggit/meta.yaml>`_

   


.. conda:package:: bioconductor-diggit

   |downloads_bioconductor-diggit| |docker_bioconductor-diggit|

   :versions: 1.16.0-0, 1.14.0-1, 1.14.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-viper: >=1.18.0,<1.19.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ks: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-diggit

   and update with::

      conda update bioconductor-diggit

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-diggit:<tag>

   (see `bioconductor-diggit/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-diggit| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-diggit.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-diggit
   :alt:   (downloads)
.. |docker_bioconductor-diggit| image:: https://quay.io/repository/biocontainers/bioconductor-diggit/status
   :target: https://quay.io/repository/biocontainers/bioconductor-diggit
.. _`bioconductor-diggit/tags`: https://quay.io/repository/biocontainers/bioconductor-diggit?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-diggit/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-diggit/README.html
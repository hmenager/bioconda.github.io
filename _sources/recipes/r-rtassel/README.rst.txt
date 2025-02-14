:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-rtassel'
.. highlight: bash

r-rtassel
=========

.. conda:recipe:: r-rtassel
   :replaces_section_title:

   R front\-end for TASSEL

   :homepage: https://bitbucket.org/bucklerlab/rtassel/wiki/Home
   :license: GPL3 / GNU GPL-3.0
   :recipe: /`r-rtassel <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-rtassel>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-rtassel/meta.yaml>`_

   


.. conda:package:: r-rtassel

   |downloads_r-rtassel| |docker_r-rtassel|

   :versions: 0.1.2019.07.25-0
   
   :depends bioconductor-genomicranges: 
   :depends bioconductor-iranges: 
   :depends bioconductor-summarizedexperiment: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-knitr: 
   :depends r-purrr: 
   :depends r-rjava: 
   :depends r-rlang: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-rtassel

   and update with::

      conda update r-rtassel

   or use the docker container::

      docker pull quay.io/biocontainers/r-rtassel:<tag>

   (see `r-rtassel/tags`_ for valid values for ``<tag>``)


.. |downloads_r-rtassel| image:: https://img.shields.io/conda/dn/bioconda/r-rtassel.svg?style=flat
   :target: https://anaconda.org/bioconda/r-rtassel
   :alt:   (downloads)
.. |docker_r-rtassel| image:: https://quay.io/repository/biocontainers/r-rtassel/status
   :target: https://quay.io/repository/biocontainers/r-rtassel
.. _`r-rtassel/tags`: https://quay.io/repository/biocontainers/r-rtassel?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-rtassel/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-rtassel/README.html
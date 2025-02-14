:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pipeframe'
.. highlight: bash

bioconductor-pipeframe
======================

.. conda:recipe:: bioconductor-pipeframe
   :replaces_section_title:

   pipeFrame is an R package for building a componentized bioinformatics pipeline. Each step in this pipeline is wrapped in the framework\, so the connection among steps is created seamlessly and automatically. Users could focus more on fine\-tuning arguments rather than spending a lot of time on transforming file format\, passing task outputs to task inputs or installing the dependencies. Componentized step elements can be customized into other new pipelines flexibly as well. This pipeline can be split into several important functional steps\, so it is much easier for users to understand the complex arguments from each step rather than parameter combination from the whole pipeline. At the same time\, componentized pipeline can restart at the breakpoint and avoid rerunning the whole pipeline\, which may save a lot of time for users on pipeline tuning or such issues as power off or process other interrupts.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/pipeFrame.html
   :license: GPL-3
   :recipe: /`bioconductor-pipeframe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pipeframe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pipeframe/meta.yaml>`_

   


.. conda:package:: bioconductor-pipeframe

   |downloads_bioconductor-pipeframe| |docker_bioconductor-pipeframe|

   :versions: 1.0.0-1
   
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-digest: 
   :depends r-magrittr: 
   :depends r-visnetwork: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pipeframe

   and update with::

      conda update bioconductor-pipeframe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pipeframe:<tag>

   (see `bioconductor-pipeframe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pipeframe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pipeframe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pipeframe
   :alt:   (downloads)
.. |docker_bioconductor-pipeframe| image:: https://quay.io/repository/biocontainers/bioconductor-pipeframe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pipeframe
.. _`bioconductor-pipeframe/tags`: https://quay.io/repository/biocontainers/bioconductor-pipeframe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pipeframe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pipeframe/README.html
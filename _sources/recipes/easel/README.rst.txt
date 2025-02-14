:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'easel'
.. highlight: bash

easel
=====

.. conda:recipe:: easel
   :replaces_section_title:

   Easel is an ANSI C code library developed by the Eddy\/Rivas laboratory at Harvard for computational analysis of biological sequences using probabilistic models.

   :homepage: https://github.com/EddyRivasLab/easel
   :license: BSD / BSD
   :recipe: /`easel <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/easel>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/easel/meta.yaml>`_

   


.. conda:package:: easel

   |downloads_easel| |docker_easel|

   :versions: 0.45-0
   
   :depends libgcc-ng: >=7.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install easel

   and update with::

      conda update easel

   or use the docker container::

      docker pull quay.io/biocontainers/easel:<tag>

   (see `easel/tags`_ for valid values for ``<tag>``)


.. |downloads_easel| image:: https://img.shields.io/conda/dn/bioconda/easel.svg?style=flat
   :target: https://anaconda.org/bioconda/easel
   :alt:   (downloads)
.. |docker_easel| image:: https://quay.io/repository/biocontainers/easel/status
   :target: https://quay.io/repository/biocontainers/easel
.. _`easel/tags`: https://quay.io/repository/biocontainers/easel?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/easel/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/easel/README.html
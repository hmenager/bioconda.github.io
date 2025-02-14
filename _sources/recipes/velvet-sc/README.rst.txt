:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'velvet-sc'
.. highlight: bash

velvet-sc
=========

.. conda:recipe:: velvet-sc
   :replaces_section_title:

   Efficient de novo assembly of single\-cell bacterial genomes from short\-read data sets

   :homepage: http://bix.ucsd.edu/projects/singlecell/
   :license: GPL / GPL-2.0
   :recipe: /`velvet-sc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/velvet-sc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/velvet-sc/meta.yaml>`_

   


.. conda:package:: velvet-sc

   |downloads_velvet-sc| |docker_velvet-sc|

   :versions: 0.7.62-2, 0.7.62-1, 0.7.62-0
   
   :depends libgcc-ng: >=4.9
   :depends perl: 
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install velvet-sc

   and update with::

      conda update velvet-sc

   or use the docker container::

      docker pull quay.io/biocontainers/velvet-sc:<tag>

   (see `velvet-sc/tags`_ for valid values for ``<tag>``)


.. |downloads_velvet-sc| image:: https://img.shields.io/conda/dn/bioconda/velvet-sc.svg?style=flat
   :target: https://anaconda.org/bioconda/velvet-sc
   :alt:   (downloads)
.. |docker_velvet-sc| image:: https://quay.io/repository/biocontainers/velvet-sc/status
   :target: https://quay.io/repository/biocontainers/velvet-sc
.. _`velvet-sc/tags`: https://quay.io/repository/biocontainers/velvet-sc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/velvet-sc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/velvet-sc/README.html
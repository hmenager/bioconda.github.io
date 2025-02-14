:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'gridss'
.. highlight: bash

gridss
======

.. conda:recipe:: gridss
   :replaces_section_title:

   GRIDSS\: a Genomic Rearrangement IDentification Software Suite

   :homepage: https://github.com/PapenfussLab/gridss
   :license: GPL / GPL-3.0
   :recipe: /`gridss <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gridss>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gridss/meta.yaml>`_
   :links: biotools: :biotools:`gridss`, doi: :doi:`10.1101/110387`

   


.. conda:package:: gridss

   |downloads_gridss| |docker_gridss|

   :versions: 2.6.2-0, 2.6.1-0, 2.6.0-0, 2.5.2-0, 2.5.1-0, 2.1.0-0, 2.0.1-0, 1.9.0-0, 1.8.1-0, 1.8.0-0, 1.7.2-2, 1.7.2-0, 1.3.4-0, 1.3.2-0, 1.3.0-0, 1.2.4-0
   
   :depends openjdk: >=8
   :depends python: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install gridss

   and update with::

      conda update gridss

   or use the docker container::

      docker pull quay.io/biocontainers/gridss:<tag>

   (see `gridss/tags`_ for valid values for ``<tag>``)


.. |downloads_gridss| image:: https://img.shields.io/conda/dn/bioconda/gridss.svg?style=flat
   :target: https://anaconda.org/bioconda/gridss
   :alt:   (downloads)
.. |docker_gridss| image:: https://quay.io/repository/biocontainers/gridss/status
   :target: https://quay.io/repository/biocontainers/gridss
.. _`gridss/tags`: https://quay.io/repository/biocontainers/gridss?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/gridss/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/gridss/README.html
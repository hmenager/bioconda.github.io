:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'megan'
.. highlight: bash

megan
=====

.. conda:recipe:: megan
   :replaces_section_title:

   A tool for studying the taxonomic content of a set of DNA reads

   :homepage: http://ab.inf.uni-tuebingen.de/software/megan6/
   :license: GPL >=3
   :recipe: /`megan <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/megan>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/megan/meta.yaml>`_
   :links: biotools: :biotools:`megan`

   


.. conda:package:: megan

   |downloads_megan| |docker_megan|

   :versions: 6.12.3-0
   
   :depends openjdk: >=8.0.144
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install megan

   and update with::

      conda update megan

   or use the docker container::

      docker pull quay.io/biocontainers/megan:<tag>

   (see `megan/tags`_ for valid values for ``<tag>``)


.. |downloads_megan| image:: https://img.shields.io/conda/dn/bioconda/megan.svg?style=flat
   :target: https://anaconda.org/bioconda/megan
   :alt:   (downloads)
.. |docker_megan| image:: https://quay.io/repository/biocontainers/megan/status
   :target: https://quay.io/repository/biocontainers/megan
.. _`megan/tags`: https://quay.io/repository/biocontainers/megan?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/megan/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/megan/README.html
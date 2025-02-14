:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'goleft'
.. highlight: bash

goleft
======

.. conda:recipe:: goleft
   :replaces_section_title:

   goleft is a collection of bioinformatics tools distributed under MIT license in a single static binary

   :homepage: https://github.com/brentp/goleft
   :license: MIT
   :recipe: /`goleft <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/goleft>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/goleft/meta.yaml>`_

   


.. conda:package:: goleft

   |downloads_goleft| |docker_goleft|

   :versions: 0.2.0-0, 0.1.18-1, 0.1.18-0, 0.1.17-0, 0.1.16-1, 0.1.16-0, 0.1.14-0, 0.1.13-1, 0.1.12-1, 0.1.12-0, 0.1.11-0, 0.1.10-0, 0.1.9-0, 0.1.8-0, 0.1.6-0, 0.1.4-0, 0.1.3-0, 0.1.2-0, 0.1.1-0, 0.1.0-0
   
   :depends samtools: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install goleft

   and update with::

      conda update goleft

   or use the docker container::

      docker pull quay.io/biocontainers/goleft:<tag>

   (see `goleft/tags`_ for valid values for ``<tag>``)


.. |downloads_goleft| image:: https://img.shields.io/conda/dn/bioconda/goleft.svg?style=flat
   :target: https://anaconda.org/bioconda/goleft
   :alt:   (downloads)
.. |docker_goleft| image:: https://quay.io/repository/biocontainers/goleft/status
   :target: https://quay.io/repository/biocontainers/goleft
.. _`goleft/tags`: https://quay.io/repository/biocontainers/goleft?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/goleft/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/goleft/README.html
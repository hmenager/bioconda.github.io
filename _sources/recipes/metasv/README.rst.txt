:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'metasv'
.. highlight: bash

metasv
======

.. conda:recipe:: metasv
   :replaces_section_title:

   An accurate and integrative structural\-variant caller for next generation sequencing

   :homepage: https://github.com/bioinform/metasv
   :license: MIT
   :recipe: /`metasv <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/metasv>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/metasv/meta.yaml>`_

   


.. conda:package:: metasv

   |downloads_metasv| |docker_metasv|

   :versions: 0.5.4-1, 0.5.4-0, 0.4.0-4, 0.4.0-3
   
   :depends age-metasv: 
   :depends pybedtools: 0.6.9
   :depends pysam: 0.7.7
   :depends python: >=2.7,<2.8.0a0
   :depends pyvcf: 0.6.7
   :depends spades: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install metasv

   and update with::

      conda update metasv

   or use the docker container::

      docker pull quay.io/biocontainers/metasv:<tag>

   (see `metasv/tags`_ for valid values for ``<tag>``)


.. |downloads_metasv| image:: https://img.shields.io/conda/dn/bioconda/metasv.svg?style=flat
   :target: https://anaconda.org/bioconda/metasv
   :alt:   (downloads)
.. |docker_metasv| image:: https://quay.io/repository/biocontainers/metasv/status
   :target: https://quay.io/repository/biocontainers/metasv
.. _`metasv/tags`: https://quay.io/repository/biocontainers/metasv?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/metasv/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/metasv/README.html
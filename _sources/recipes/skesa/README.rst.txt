:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'skesa'
.. highlight: bash

skesa
=====

.. conda:recipe:: skesa
   :replaces_section_title:

   Strategic Kmer Extension for Scrupulous Assemblies

   :homepage: https://ftp.ncbi.nlm.nih.gov/pub/agarwala/skesa
   :license: Public Domain
   :recipe: /`skesa <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/skesa>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/skesa/meta.yaml>`_

   


.. conda:package:: skesa

   |downloads_skesa| |docker_skesa|

   :versions: 2.3.0-2, 2.3.0-1, 2.3.0-0, 2.2-2, 2.2-1, 2.1-0
   
   :depends boost: >=1.70.0,<1.70.1.0a0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install skesa

   and update with::

      conda update skesa

   or use the docker container::

      docker pull quay.io/biocontainers/skesa:<tag>

   (see `skesa/tags`_ for valid values for ``<tag>``)


.. |downloads_skesa| image:: https://img.shields.io/conda/dn/bioconda/skesa.svg?style=flat
   :target: https://anaconda.org/bioconda/skesa
   :alt:   (downloads)
.. |docker_skesa| image:: https://quay.io/repository/biocontainers/skesa/status
   :target: https://quay.io/repository/biocontainers/skesa
.. _`skesa/tags`: https://quay.io/repository/biocontainers/skesa?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/skesa/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/skesa/README.html
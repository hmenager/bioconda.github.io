:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'anise_basil'
.. highlight: bash

anise_basil
===========

.. conda:recipe:: anise_basil
   :replaces_section_title:

   BASIL is a method to detect breakpoints for structural variants \(including insertion breakpoints\) from aligned paired HTS reads in BAM format. ANISE is a method for the assembly of large insertions from paired reads in BAM format and a list candidate insert breakpoints as generated by BASIL.

   :homepage: https://github.com/seqan/anise_basil
   :license: BSD
   :recipe: /`anise_basil <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/anise_basil>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/anise_basil/meta.yaml>`_
   :links: doi: :doi:`10.1093/bioinformatics/btv051`

   


.. conda:package:: anise_basil

   |downloads_anise_basil| |docker_anise_basil|

   :versions: 1.2.0-0
   
   :depends libgcc-ng: >=4.9
   :depends libstdcxx-ng: >=4.9
   :depends python: >=2.7,<2.8.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install anise_basil

   and update with::

      conda update anise_basil

   or use the docker container::

      docker pull quay.io/biocontainers/anise_basil:<tag>

   (see `anise_basil/tags`_ for valid values for ``<tag>``)


.. |downloads_anise_basil| image:: https://img.shields.io/conda/dn/bioconda/anise_basil.svg?style=flat
   :target: https://anaconda.org/bioconda/anise_basil
   :alt:   (downloads)
.. |docker_anise_basil| image:: https://quay.io/repository/biocontainers/anise_basil/status
   :target: https://quay.io/repository/biocontainers/anise_basil
.. _`anise_basil/tags`: https://quay.io/repository/biocontainers/anise_basil?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/anise_basil/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/anise_basil/README.html
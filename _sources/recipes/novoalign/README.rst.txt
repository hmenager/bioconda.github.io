:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'novoalign'
.. highlight: bash

novoalign
=========

.. conda:recipe:: novoalign
   :replaces_section_title:

   Powerful tool designed for mapping of short reads onto a reference genome from Illumina\, Ion Torrent\, and 454 NGS platforms

   :homepage: http://www.novocraft.com/products/novoalign/
   :license: Commercial (requires license for commercial use or for features likes multi-threading)
   :recipe: /`novoalign <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/novoalign>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/novoalign/meta.yaml>`_
   :links: biotools: :biotools:`Novoalign`

   


.. conda:package:: novoalign

   |downloads_novoalign| |docker_novoalign|

   :versions: 3.09.00-2, 3.09.00-1, 3.09.00-0, 3.07.00-1, 3.07.00-0, 3.06.05-0, 3.04.04-3, 3.04.04-2, 3.04.04-0, 3.03.02-0
   
   :depends curl: >=7.59.0,<8.0a0
   :depends libgcc-ng: >=4.9
   :depends libstdcxx-ng: >=4.9
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install novoalign

   and update with::

      conda update novoalign

   or use the docker container::

      docker pull quay.io/biocontainers/novoalign:<tag>

   (see `novoalign/tags`_ for valid values for ``<tag>``)


.. |downloads_novoalign| image:: https://img.shields.io/conda/dn/bioconda/novoalign.svg?style=flat
   :target: https://anaconda.org/bioconda/novoalign
   :alt:   (downloads)
.. |docker_novoalign| image:: https://quay.io/repository/biocontainers/novoalign/status
   :target: https://quay.io/repository/biocontainers/novoalign
.. _`novoalign/tags`: https://quay.io/repository/biocontainers/novoalign?tab=tags






Notes
-----
Novoalign runs in single\-threaded mode by default unless a \"novoalign.lic\" license file is provided in the same directory as its binaries. The license file can be copied in to the conda environment via the \"novoalign\-license\-register\" command.


Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/novoalign/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/novoalign/README.html
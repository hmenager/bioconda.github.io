:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'seqan_tcoffee'
.. highlight: bash

seqan_tcoffee
=============

.. conda:recipe:: seqan_tcoffee
   :replaces_section_title:

   SeqAn\:\:T\-Coffee \- Multiple Sequence Alignment

   :homepage: http://www.seqan.de/apps/seqan-t-coffee/
   :license: GPLv3
   :recipe: /`seqan_tcoffee <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/seqan_tcoffee>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/seqan_tcoffee/meta.yaml>`_

   


.. conda:package:: seqan_tcoffee

   |downloads_seqan_tcoffee| |docker_seqan_tcoffee|

   :versions: 1.13.3-2, 1.13.3-1, 1.13.3-0
   
   :depends bzip2: >=1.0.6,<2.0a0
   :depends libstdcxx-ng: >=4.9
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install seqan_tcoffee

   and update with::

      conda update seqan_tcoffee

   or use the docker container::

      docker pull quay.io/biocontainers/seqan_tcoffee:<tag>

   (see `seqan_tcoffee/tags`_ for valid values for ``<tag>``)


.. |downloads_seqan_tcoffee| image:: https://img.shields.io/conda/dn/bioconda/seqan_tcoffee.svg?style=flat
   :target: https://anaconda.org/bioconda/seqan_tcoffee
   :alt:   (downloads)
.. |docker_seqan_tcoffee| image:: https://quay.io/repository/biocontainers/seqan_tcoffee/status
   :target: https://quay.io/repository/biocontainers/seqan_tcoffee
.. _`seqan_tcoffee/tags`: https://quay.io/repository/biocontainers/seqan_tcoffee?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/seqan_tcoffee/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/seqan_tcoffee/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'addrg'
.. highlight: bash

addrg
=====

.. conda:recipe:: addrg
   :replaces_section_title:

   Add read group to BAM files

   :homepage: https://github.com/holtgrewe/addrg
   :license: MIT
   :recipe: /`addrg <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/addrg>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/addrg/meta.yaml>`_

   


.. conda:package:: addrg

   |downloads_addrg| |docker_addrg|

   :versions: 0.2.1-4, 0.2.1-3, 0.2.1-2, 0.2.1-1, 0.2.1-0, 0.2-0, 0.1-0
   
   :depends htslib: >=1.9,<1.10.0a0
   :depends libgcc-ng: >=7.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install addrg

   and update with::

      conda update addrg

   or use the docker container::

      docker pull quay.io/biocontainers/addrg:<tag>

   (see `addrg/tags`_ for valid values for ``<tag>``)


.. |downloads_addrg| image:: https://img.shields.io/conda/dn/bioconda/addrg.svg?style=flat
   :target: https://anaconda.org/bioconda/addrg
   :alt:   (downloads)
.. |docker_addrg| image:: https://quay.io/repository/biocontainers/addrg/status
   :target: https://quay.io/repository/biocontainers/addrg
.. _`addrg/tags`: https://quay.io/repository/biocontainers/addrg?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/addrg/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/addrg/README.html
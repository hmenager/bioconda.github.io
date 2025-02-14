:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'locarna'
.. highlight: bash

locarna
=======

.. conda:recipe:: locarna
   :replaces_section_title:

   Multiple alignment of RNAs

   :homepage: http://www.bioinf.uni-freiburg.de/Software/LocARNA/
   :license: GPL
   :recipe: /`locarna <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/locarna>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/locarna/meta.yaml>`_
   :links: biotools: :biotools:`locarna`, doi: :doi:`10.1371/journal.pcbi.0030065`

   


.. conda:package:: locarna

   |downloads_locarna| |docker_locarna|

   :versions: 2.0.0RC8-0, 1.9.2.3-0, 1.9.2-1, 1.9.2-0, 1.9.1-2, 1.9.1-1, 1.9.1-0, 1.9.0-0, 1.8.12-0, 1.8.11-1, 1.8.10-0, 1.8.9-3, 1.8.9-2, 1.8.9-1, 1.8.7-1, 1.8.7-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends perl: 
   :depends viennarna: 2.4.13
   :depends viennarna: >=2.4.13,<2.5.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install locarna

   and update with::

      conda update locarna

   or use the docker container::

      docker pull quay.io/biocontainers/locarna:<tag>

   (see `locarna/tags`_ for valid values for ``<tag>``)


.. |downloads_locarna| image:: https://img.shields.io/conda/dn/bioconda/locarna.svg?style=flat
   :target: https://anaconda.org/bioconda/locarna
   :alt:   (downloads)
.. |docker_locarna| image:: https://quay.io/repository/biocontainers/locarna/status
   :target: https://quay.io/repository/biocontainers/locarna
.. _`locarna/tags`: https://quay.io/repository/biocontainers/locarna?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/locarna/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/locarna/README.html
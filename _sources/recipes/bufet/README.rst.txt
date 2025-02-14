:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bufet'
.. highlight: bash

bufet
=====

.. conda:recipe:: bufet
   :replaces_section_title:

   Tool that performs the unbiased miRNA functional enrichment analysis \(Bleazard et al.\) requiring significantly reduced excution times \(less than 10 minutes for 1 million iterations\).

   :homepage: https://github.com/diwis/BUFET/
   :license: file
   :recipe: /`bufet <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bufet>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bufet/meta.yaml>`_
   :links: biotools: :biotools:`BUFET`, doi: :doi:`10.1186/s12859-017-1812-8`

   


.. conda:package:: bufet

   |downloads_bufet| |docker_bufet|

   :versions: 1.0-0
   
   :depends libgcc-ng: >=4.9
   :depends python: >=2.7,<2.8.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bufet

   and update with::

      conda update bufet

   or use the docker container::

      docker pull quay.io/biocontainers/bufet:<tag>

   (see `bufet/tags`_ for valid values for ``<tag>``)


.. |downloads_bufet| image:: https://img.shields.io/conda/dn/bioconda/bufet.svg?style=flat
   :target: https://anaconda.org/bioconda/bufet
   :alt:   (downloads)
.. |docker_bufet| image:: https://quay.io/repository/biocontainers/bufet/status
   :target: https://quay.io/repository/biocontainers/bufet
.. _`bufet/tags`: https://quay.io/repository/biocontainers/bufet?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bufet/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bufet/README.html
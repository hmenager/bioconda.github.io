:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'gdc'
.. highlight: bash

gdc
===

.. conda:recipe:: gdc
   :replaces_section_title:

   Utility designed for compression of genome collections from the same species.

   :homepage: http://sun.aei.polsl.pl/REFRESH/index.php?page=projects&project=gdc&subpage=about
   :license: GPL2
   :recipe: /`gdc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gdc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gdc/meta.yaml>`_
   :links: biotools: :biotools:`GDC`, doi: :doi:`10.1038/srep11565`

   


.. conda:package:: gdc

   |downloads_gdc| |docker_gdc|

   :versions: 2.0-0
   
   :depends libstdcxx-ng: >=4.9
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install gdc

   and update with::

      conda update gdc

   or use the docker container::

      docker pull quay.io/biocontainers/gdc:<tag>

   (see `gdc/tags`_ for valid values for ``<tag>``)


.. |downloads_gdc| image:: https://img.shields.io/conda/dn/bioconda/gdc.svg?style=flat
   :target: https://anaconda.org/bioconda/gdc
   :alt:   (downloads)
.. |docker_gdc| image:: https://quay.io/repository/biocontainers/gdc/status
   :target: https://quay.io/repository/biocontainers/gdc
.. _`gdc/tags`: https://quay.io/repository/biocontainers/gdc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/gdc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/gdc/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'vdjer'
.. highlight: bash

vdjer
=====

.. conda:recipe:: vdjer
   :replaces_section_title:

   B Cell Receptor Repertoire Reconstruction from short read mRNA\-Seq data

   :homepage: https://github.com/mozack/vdjer
   :license: https://github.com/mozack/vdjer/blob/master/LICENSE.txt
   :recipe: /`vdjer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/vdjer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/vdjer/meta.yaml>`_

   


.. conda:package:: vdjer

   |downloads_vdjer| |docker_vdjer|

   :versions: 0.12-2, 0.12-1, 0.12-0
   
   :depends libgcc-ng: >=4.9
   :depends libstdcxx-ng: >=4.9
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install vdjer

   and update with::

      conda update vdjer

   or use the docker container::

      docker pull quay.io/biocontainers/vdjer:<tag>

   (see `vdjer/tags`_ for valid values for ``<tag>``)


.. |downloads_vdjer| image:: https://img.shields.io/conda/dn/bioconda/vdjer.svg?style=flat
   :target: https://anaconda.org/bioconda/vdjer
   :alt:   (downloads)
.. |docker_vdjer| image:: https://quay.io/repository/biocontainers/vdjer/status
   :target: https://quay.io/repository/biocontainers/vdjer
.. _`vdjer/tags`: https://quay.io/repository/biocontainers/vdjer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/vdjer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/vdjer/README.html
:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'illumina-interop'
.. highlight: bash

illumina-interop
================

.. conda:recipe:: illumina-interop
   :replaces_section_title:

   The Illumina InterOp libraries are a set of common routines used for reading and writing InterOp metric files. These metric files are binary files produced during a run providing detailed statistics about a run. In a few cases\, the metric files are produced after a run during secondary analysis \(index metrics\) or for faster display of a subset of the original data \(collapsed quality scores\).

   :homepage: http://illumina.github.io/interop/index.html
   :developer docs: https://github.com/Illumina/interop
   :license: GPL / GPL-3.0
   :recipe: /`illumina-interop <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/illumina-interop>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/illumina-interop/meta.yaml>`_

   


.. conda:package:: illumina-interop

   |downloads_illumina-interop| |docker_illumina-interop|

   :versions: 1.1.8-0, 1.1.7-0, 1.1.6-0, 1.1.4-3, 1.1.4-0, 1.0.25-1, 1.0.25-0
   
   :depends libgcc-ng: >=4.9
   :depends libstdcxx-ng: >=4.9
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install illumina-interop

   and update with::

      conda update illumina-interop

   or use the docker container::

      docker pull quay.io/biocontainers/illumina-interop:<tag>

   (see `illumina-interop/tags`_ for valid values for ``<tag>``)


.. |downloads_illumina-interop| image:: https://img.shields.io/conda/dn/bioconda/illumina-interop.svg?style=flat
   :target: https://anaconda.org/bioconda/illumina-interop
   :alt:   (downloads)
.. |docker_illumina-interop| image:: https://quay.io/repository/biocontainers/illumina-interop/status
   :target: https://quay.io/repository/biocontainers/illumina-interop
.. _`illumina-interop/tags`: https://quay.io/repository/biocontainers/illumina-interop?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/illumina-interop/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/illumina-interop/README.html
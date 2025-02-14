:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'picard-slim'
.. highlight: bash

picard-slim
===========

.. conda:recipe:: picard-slim
   :replaces_section_title:

   Java tools for working with NGS data in the BAM format.

   :homepage: http://broadinstitute.github.io/picard/
   :developer docs: https://github.com/broadinstitute/picard
   :license: MIT / MIT
   :recipe: /`picard-slim <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/picard-slim>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/picard-slim/meta.yaml>`_

   Java tools for working with NGS data in the BAM format. This package lacks the R dependency that is only required for some metrics tasks. This keeps the size of the package smaller\, at the cost of breaking some of Picards\'s commands. The \'picard\' package contains all the necessary dependencies.


.. conda:package:: picard-slim

   |downloads_picard-slim| |docker_picard-slim|

   :versions: 2.20.8-0, 2.20.7-0, 2.20.6-0, 2.20.5-0, 2.20.4-0
   
   :depends openjdk: >=8
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install picard-slim

   and update with::

      conda update picard-slim

   or use the docker container::

      docker pull quay.io/biocontainers/picard-slim:<tag>

   (see `picard-slim/tags`_ for valid values for ``<tag>``)


.. |downloads_picard-slim| image:: https://img.shields.io/conda/dn/bioconda/picard-slim.svg?style=flat
   :target: https://anaconda.org/bioconda/picard-slim
   :alt:   (downloads)
.. |docker_picard-slim| image:: https://quay.io/repository/biocontainers/picard-slim/status
   :target: https://quay.io/repository/biocontainers/picard-slim
.. _`picard-slim/tags`: https://quay.io/repository/biocontainers/picard-slim?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/picard-slim/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/picard-slim/README.html
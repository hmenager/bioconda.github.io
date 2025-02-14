:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'snakeparse'
.. highlight: bash

snakeparse
==========

.. conda:recipe:: snakeparse
   :replaces_section_title:

   Making Snakemake workflows into full\-fledged command line tools since 1999.

   :homepage: https://github.com/nh13/snakeparse
   :license: MIT
   :recipe: /`snakeparse <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/snakeparse>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/snakeparse/meta.yaml>`_

   


.. conda:package:: snakeparse

   |downloads_snakeparse| |docker_snakeparse|

   :versions: 0.1.0-1, 0.1.0-0, 0.0.1-0
   
   :depends pyhocon: >=0.3.38
   :depends python: >=3.6,<3.7.0a0
   :depends pyyaml: >=3.12
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install snakeparse

   and update with::

      conda update snakeparse

   or use the docker container::

      docker pull quay.io/biocontainers/snakeparse:<tag>

   (see `snakeparse/tags`_ for valid values for ``<tag>``)


.. |downloads_snakeparse| image:: https://img.shields.io/conda/dn/bioconda/snakeparse.svg?style=flat
   :target: https://anaconda.org/bioconda/snakeparse
   :alt:   (downloads)
.. |docker_snakeparse| image:: https://quay.io/repository/biocontainers/snakeparse/status
   :target: https://quay.io/repository/biocontainers/snakeparse
.. _`snakeparse/tags`: https://quay.io/repository/biocontainers/snakeparse?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/snakeparse/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/snakeparse/README.html
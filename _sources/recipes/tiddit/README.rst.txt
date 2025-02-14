:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'tiddit'
.. highlight: bash

tiddit
======

.. conda:recipe:: tiddit
   :replaces_section_title:

   TIDDIT \- structural variant calling.

   :homepage: https://github.com/SciLifeLab/TIDDIT
   :license: GPL-3
   :recipe: /`tiddit <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/tiddit>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/tiddit/meta.yaml>`_

   


.. conda:package:: tiddit

   |downloads_tiddit| |docker_tiddit|

   :versions: 2.8.0-0, 2.7.1-1, 2.7.1-0, 2.6.0-0
   
   :depends cmake: 
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends numpy: 
   :depends pysam: 
   :depends python: >=2.7,<2.8.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install tiddit

   and update with::

      conda update tiddit

   or use the docker container::

      docker pull quay.io/biocontainers/tiddit:<tag>

   (see `tiddit/tags`_ for valid values for ``<tag>``)


.. |downloads_tiddit| image:: https://img.shields.io/conda/dn/bioconda/tiddit.svg?style=flat
   :target: https://anaconda.org/bioconda/tiddit
   :alt:   (downloads)
.. |docker_tiddit| image:: https://quay.io/repository/biocontainers/tiddit/status
   :target: https://quay.io/repository/biocontainers/tiddit
.. _`tiddit/tags`: https://quay.io/repository/biocontainers/tiddit?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/tiddit/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/tiddit/README.html
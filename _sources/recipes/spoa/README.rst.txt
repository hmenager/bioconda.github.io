:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'spoa'
.. highlight: bash

spoa
====

.. conda:recipe:: spoa
   :replaces_section_title:

   SIMD partial order alignment tool\/library

   :homepage: https://github.com/rvaser/spoa
   :license: MIT
   :recipe: /`spoa <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/spoa>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/spoa/meta.yaml>`_

   


.. conda:package:: spoa

   |downloads_spoa| |docker_spoa|

   :versions: 3.0.0-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install spoa

   and update with::

      conda update spoa

   or use the docker container::

      docker pull quay.io/biocontainers/spoa:<tag>

   (see `spoa/tags`_ for valid values for ``<tag>``)


.. |downloads_spoa| image:: https://img.shields.io/conda/dn/bioconda/spoa.svg?style=flat
   :target: https://anaconda.org/bioconda/spoa
   :alt:   (downloads)
.. |docker_spoa| image:: https://quay.io/repository/biocontainers/spoa/status
   :target: https://quay.io/repository/biocontainers/spoa
.. _`spoa/tags`: https://quay.io/repository/biocontainers/spoa?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/spoa/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/spoa/README.html
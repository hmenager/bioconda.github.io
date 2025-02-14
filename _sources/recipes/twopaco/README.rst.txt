:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'twopaco'
.. highlight: bash

twopaco
=======

.. conda:recipe:: twopaco
   :replaces_section_title:

   A fast constructor of the compressed de Bruijn graph from many genomes.

   :homepage: https://github.com/medvedevgroup/TwoPaCo
   :license: Custom OSS
   :recipe: /`twopaco <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/twopaco>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/twopaco/meta.yaml>`_

   


.. conda:package:: twopaco

   |downloads_twopaco| |docker_twopaco|

   :versions: 0.9.2-2, 0.9.2-0
   
   :depends libgcc-ng: >=4.9
   :depends libstdcxx-ng: >=4.9
   :depends tbb: >=2019.1
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install twopaco

   and update with::

      conda update twopaco

   or use the docker container::

      docker pull quay.io/biocontainers/twopaco:<tag>

   (see `twopaco/tags`_ for valid values for ``<tag>``)


.. |downloads_twopaco| image:: https://img.shields.io/conda/dn/bioconda/twopaco.svg?style=flat
   :target: https://anaconda.org/bioconda/twopaco
   :alt:   (downloads)
.. |docker_twopaco| image:: https://quay.io/repository/biocontainers/twopaco/status
   :target: https://quay.io/repository/biocontainers/twopaco
.. _`twopaco/tags`: https://quay.io/repository/biocontainers/twopaco?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/twopaco/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/twopaco/README.html
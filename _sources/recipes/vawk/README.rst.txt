:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'vawk'
.. highlight: bash

vawk
====

.. conda:recipe:: vawk
   :replaces_section_title:

   An awk\-like VCF parser

   :homepage: https://github.com/cc2qe/vawk
   :license: MIT / MIT
   :recipe: /`vawk <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/vawk>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/vawk/meta.yaml>`_

   


.. conda:package:: vawk

   |downloads_vawk| |docker_vawk|

   :versions: 0.0.2-4, 0.0.2-3, 0.0.2-1, 0.0.2-0
   
   :depends gawk: 
   :depends python: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install vawk

   and update with::

      conda update vawk

   or use the docker container::

      docker pull quay.io/biocontainers/vawk:<tag>

   (see `vawk/tags`_ for valid values for ``<tag>``)


.. |downloads_vawk| image:: https://img.shields.io/conda/dn/bioconda/vawk.svg?style=flat
   :target: https://anaconda.org/bioconda/vawk
   :alt:   (downloads)
.. |docker_vawk| image:: https://quay.io/repository/biocontainers/vawk/status
   :target: https://quay.io/repository/biocontainers/vawk
.. _`vawk/tags`: https://quay.io/repository/biocontainers/vawk?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/vawk/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/vawk/README.html
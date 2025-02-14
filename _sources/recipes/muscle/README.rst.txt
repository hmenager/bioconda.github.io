:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'muscle'
.. highlight: bash

muscle
======

.. conda:recipe:: muscle
   :replaces_section_title:

   MUSCLE\: multiple sequence alignment with high accuracy and high throughput

   :homepage: http://www.drive5.com/muscle/
   :license: http://www.drive5.com/muscle/manual/license.html
   :recipe: /`muscle <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/muscle>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/muscle/meta.yaml>`_
   :links: biotools: :biotools:`muscle`

   


.. conda:package:: muscle

   |downloads_muscle| |docker_muscle|

   :versions: 3.8.1551-4, 3.8.1551-3, 3.8.1551-2, 3.8.1551-1, 3.8.31-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install muscle

   and update with::

      conda update muscle

   or use the docker container::

      docker pull quay.io/biocontainers/muscle:<tag>

   (see `muscle/tags`_ for valid values for ``<tag>``)


.. |downloads_muscle| image:: https://img.shields.io/conda/dn/bioconda/muscle.svg?style=flat
   :target: https://anaconda.org/bioconda/muscle
   :alt:   (downloads)
.. |docker_muscle| image:: https://quay.io/repository/biocontainers/muscle/status
   :target: https://quay.io/repository/biocontainers/muscle
.. _`muscle/tags`: https://quay.io/repository/biocontainers/muscle?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/muscle/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/muscle/README.html
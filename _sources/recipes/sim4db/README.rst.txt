:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'sim4db'
.. highlight: bash

sim4db
======

.. conda:recipe:: sim4db
   :replaces_section_title:

   Sim4db and leaff\: Utilities for fast batch spliced alignment and sequence indexing

   :homepage: http://kmer.sourceforge.net/wiki/index.php/Getting_Started_with_Sim4db
   :license: GPL
   :recipe: /`sim4db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sim4db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sim4db/meta.yaml>`_

   


.. conda:package:: sim4db

   |downloads_sim4db| |docker_sim4db|

   :versions: 2008-0
   
   :depends libgcc: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install sim4db

   and update with::

      conda update sim4db

   or use the docker container::

      docker pull quay.io/biocontainers/sim4db:<tag>

   (see `sim4db/tags`_ for valid values for ``<tag>``)


.. |downloads_sim4db| image:: https://img.shields.io/conda/dn/bioconda/sim4db.svg?style=flat
   :target: https://anaconda.org/bioconda/sim4db
   :alt:   (downloads)
.. |docker_sim4db| image:: https://quay.io/repository/biocontainers/sim4db/status
   :target: https://quay.io/repository/biocontainers/sim4db
.. _`sim4db/tags`: https://quay.io/repository/biocontainers/sim4db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/sim4db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/sim4db/README.html
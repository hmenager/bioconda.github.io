:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'piranha'
.. highlight: bash

piranha
=======

.. conda:recipe:: piranha
   :replaces_section_title:

   Piranha is a peak\-caller for CLIP\- and RIP\-Seq data.

   :homepage: http://smithlabresearch.org/software/piranha/
   :license: GNU General Public License v3 (GPLv3)
   :recipe: /`piranha <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/piranha>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/piranha/meta.yaml>`_

   


.. conda:package:: piranha

   |downloads_piranha| |docker_piranha|

   :versions: 1.2.1-7, 1.2.1-6, 1.2.1-5, 1.2.1-3, 1.2.1-2, 1.2.1-1, 1.2.1-0
   
   :depends bamtools: >=2.5.1,<2.5.2.0a0
   :depends gsl: >=2.4,<2.5.0a0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install piranha

   and update with::

      conda update piranha

   or use the docker container::

      docker pull quay.io/biocontainers/piranha:<tag>

   (see `piranha/tags`_ for valid values for ``<tag>``)


.. |downloads_piranha| image:: https://img.shields.io/conda/dn/bioconda/piranha.svg?style=flat
   :target: https://anaconda.org/bioconda/piranha
   :alt:   (downloads)
.. |docker_piranha| image:: https://quay.io/repository/biocontainers/piranha/status
   :target: https://quay.io/repository/biocontainers/piranha
.. _`piranha/tags`: https://quay.io/repository/biocontainers/piranha?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/piranha/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/piranha/README.html
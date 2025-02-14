:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'abyss'
.. highlight: bash

abyss
=====

.. conda:recipe:: abyss
   :replaces_section_title:

   Assembly By Short Sequences \- a de novo\, parallel\, paired\-end sequence assembler

   :homepage: http://www.bcgsc.ca/platform/bioinfo/software/abyss
   :documentation: https://github.com/bcgsc/abyss#readme
   
   :developer docs: https://github.com/bcgsc/abyss
   :license: GPL3
   :recipe: /`abyss <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/abyss>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/abyss/meta.yaml>`_
   :links: biotools: :biotools:`abyss`, doi: :doi:`10.1101/gr.214346.116`, doi: :doi:`10.1101/gr.089532.108`

   


.. conda:package:: abyss

   |downloads_abyss| |docker_abyss|

   :versions: 2.2.3-0, 2.2.2-0, 2.2.1-0, 2.1.5-1, 2.1.5-0, 2.1.4-0, 2.1.3-0, 2.1.1-0, 2.1.0-0, 2.0.2-5, 2.0.2-4, 2.0.2-3, 2.0.2-2, 2.0.2-1, 2.0.2-0, 2.0.1-2, 2.0.1-1, 2.0.1-0, 1.9.0-7, 1.9.0-6, 1.9.0-5, 1.9.0-4, 1.9.0-3, 1.9.0-2, 1.9.0-1, 1.9.0-0, 1.5.2-5, 1.5.2-4, 1.5.2-3, 1.5.2-2, 1.5.2-1, 1.5.2-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends make: 
   :depends openmpi: >=4.0.1,<4.1.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install abyss

   and update with::

      conda update abyss

   or use the docker container::

      docker pull quay.io/biocontainers/abyss:<tag>

   (see `abyss/tags`_ for valid values for ``<tag>``)


.. |downloads_abyss| image:: https://img.shields.io/conda/dn/bioconda/abyss.svg?style=flat
   :target: https://anaconda.org/bioconda/abyss
   :alt:   (downloads)
.. |docker_abyss| image:: https://quay.io/repository/biocontainers/abyss/status
   :target: https://quay.io/repository/biocontainers/abyss
.. _`abyss/tags`: https://quay.io/repository/biocontainers/abyss?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/abyss/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/abyss/README.html